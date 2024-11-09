# Dataset Version 1

## Dataset Focused Proposal
Our group’s primary focus will be analyzing baseball statistics to uncover trends and patterns within the sport. We aim to answer the following research questions:
    
Has it changed how people consume the sport? Hyper-analyzing?  
Sports gambling has become a huge focus.  
What meaning is the data collected now? What impact does it have?

## Where we got our data
Our group collected our data from https://baseballsavant.mlb.com/; where we can download the CSV file of any filtered list. Essentially, if you wanted to only take a look at the best batters and nothing else, you are able to filter that out and then be able to download the CSV straight away.

### Scope
This dataset is built off of a selection of 12 statistics from players with over 100 Plate appearances.  
This gives a wide but manageable list of players their range of success in each of these statistics.
We plan to expand the scope to include sports betting and gambling data; we will make observations regarding the collection methods, meaning, and consumption of baseball statistics and how they have changed over time in relation to the rise of sports gambling.

## Documentation
### Process & Choices
Originally there were plans to scrape the desired data, however most websites that we identified do not allow webscraping without strict regulations and limited use-cases. Due to not being able to webscrape on certain sites, we went looking into other sites and eventually found that baseballsavant.mlb.com had a tool that allowed for easy data collection; the tool allows the user to filter players, games, and teams with certain parameters and export the data to csv format. To start, our goal was to get the statistics of players with over 100 plate appearances (Pa), so there would be a fair amount of data behind each player and to exclude the extremely low end of appearances. If deemed necessary, we can easily collect more data.


### Content Description
We picked 12 common baseball parameters with a slight focus on betting parameters.  
They are:  
Pa = Plate appearances.  
K% = Strikeout percentage.  
BB% = Walked percentage.  
wOBA = Weighted on-base average.   
xwOBA = Expected weighted on-base average.  
Sweet Spot % = How often a player hits a ball at the optimal launch angle (8-32 degrees).  
Barrel % = % of batted balls that meet ideal criteria for exit velocity & angle.  
Hard Hit % = % of balls hit with an exit velocity >95 mph. Indicates the frequency of this event.  
Avg Best Speed = Avg speed of the players best hit balls. Indicates top-level hitting power.  
Avg Hyper Speed = Indicates players average speed on balls hit with extreme force or exit velocity. Maximum Strength.  
Whiff % = % of a player's swings that completely miss the ball. High % indicates a swing-and-miss issue or an aggressive batting approach.  
Swing % = The % of pitches a player swings at. Shows their level of aggressiveness at the plate.  

All of these stats can be used to see how well a certain player is performing and what his strengths and weaknesses are. This can allow for people to make educated bets when sports betting. We made sure to include statistics from the new Statcast tool, which uses high-fidelity sensors to make accurate measurements regarding ball speed, batting angles, and many other quantifications. We plan to use these modern statistics in conjunction with older, historic baseball statistics to identify changes over time. 

### Responsibility & Contribution
- Yosef: Collecting data, coding
- Nick: Writing
- Ethan: Editing / Writing 
