# Dataset Version 1

## Dataset Focused Proposal
Our group’s primary focus will be analyzing baseball statistics to uncover trends and patterns within the sport. We aim to answer the following research questions:
    
Has it changed how people consume the sport? Hyper-analyzing?  
Sports gambling has become a huge focus.  
What meaning is the data collected now? What impact does it have?  

### Scope
This dataset is built off of a selection of 12 statistics from players with over 100 Plate appearances.  
This gives a wide but manageable list of players their range of success in each of these statistics.

## Documentation
### Process & Choices
Originally there were plans to try and webscrape the desired data but due to some cites not allowing webscraping and others requiring it to be done in specific ways, it wasn't worth it. Due to not being able to webscrape on certain sites, we went looking into other sites and eventually found that baseballsavant.mlb.com had a custom leaderboard generator that you could export to a csv. Our goal was to then get the stats of players with over 100 plate appearances (Pa) so there would be a fair amount of data behind each player and to exclude the extremely low end of appearances.


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

All of these stats can be used to see how well a certain player is performing and what his strengths and weaknesses are. This can allow for people to make educated bets when sports betting.  

### Responsibility & Contribution
- Yosef: Coding part
- Nick: Writing
