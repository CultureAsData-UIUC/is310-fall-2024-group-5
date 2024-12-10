# Experimenting With Datasets

See division of labour at bottom of this sheet.

## New Dataset

Our previous dataset was lacking magnitude, depth, and context. So, we made a few changes.

- Incorporated many more years

    - Every ~5 years since 1871

- Incorporated many more leagues

    - Previously, we had solely the MLB
    - Now, we have every single baseball major league, active and inactive
    
        - Including various regional and segregated leagues.

- Incorporated many more variables

    - For each year, we collected all available data regarding batting, pitching, and league team rankings.

- Including metadata

    - Minimal cleaning and filtering

In addition, we cultivated a second dataset to represent the humanties-side of the history of baseball. 

    - Used the Chronicling America API with the Requests library to collect information regarding the reporting of baseball leagues over time


## Dataset Utility

By combining records from different sources, leagues, and eras, we can observe differences in how data was recorded and kept between leagues and over time.

The Chronicling America data can be used to examine the times, geographical locations, as well as specific newspapers that reported on various leagues.

### Examining Data
- We can examine the variables used to measure performance between different leagues; is it true that less popular leagues performed worse?
- We can examine changes in variables over time; has overall performance increased over time, in parallel with rising popularity?

### Examining Metadata
- We can examine the amount parameters recorded in any given year between the Major League Baseball (MLB) and National Negro League (NNL). 
- Similarly, we can compare the amount of missing values between leagues. 

### Future Use
Strengths:
- No dataset exists with all of the data we have collected in the format we have it in
- The dataset includes varibales and statistics from many major leagues and not just the MLB and contains an exhaustive amount of statistics
- The dataset includes the missing_value_count which allow future users to see any areas that may need t be excluded or reworked for future analysis

Weaknesses:
- Missing things like Mexican Baseball League (LMB) and likely other leagues' stats as they are not available on baseball reference
- Data was taken every 5 years but there are likley leagues that existed for less than that time
- Data collection started in 1871 and leagues could have existed before then
- The dataset does not have contextual factors such as rule changes or other events that have changed the game significantly
- There is no player level stats to do in depth individual analysis
- Practices of how to record statistics have changed over time in the MLB which is described more thouroughly in the article below:
 '<https://sabr.org/journal/article/all-the-record-books-are-wrong/>'  
For example, for a starting pitcher to qualify for a win in today's MLB, a starting pitcher must pitch at least 5 innings in the game, and after the pitcher exits the game, his/her team must not give up the lead the pitcher had when he/she exited. This is different from how the win stat used to be given. As described in the article, the first practice that was used from (1876-1904) for pitching wins was that if a starting pitcher left the game with the lead and the lead was never given up the rest of the game, they would receive the win. This differs from today's practice of the starting pitcher having to pitch at least 5 innings to receive a win. What this article describes is that some record books wrongly gave pitchers wins based on the current times practices and not the practices of when the pitchers played. This is a weakness because some rulebooks may be wrong to due incorrectly retroactively recording statistics.
- We were never able to import data from a seperate statistics website call Baseball Savant due to how time consuming the process was.

Potential Applications:
- Data can be used to predict trends and how leagues and stats will look in the future:
- For example as we can see from a quick and basic analysis, things like Hits (H), and Runs (R), continue to rise over time and even though they take a few recent dips, generally seaking, those numbers continue to rise and will likely stay on the same trajectory as the game and technology evolves
- Era Comparisons:
- Similarly to predicting trends, stats over different eras can be compared to identify impacts on the game for example the steroid era
- Other Visualization and Causality Models:
- In the future, any variables can be tested against each other or over time to see how they affect one another and how the variables change over time
## Computational Methods (TO BE COMPLETED)


## Division of Labour

- **Data Collection:** We overhauled our dataset. There exist APIs that may have been useful in this process, however the individuals that designed these APIs hand-picked which pieces of data are accessible via the APIs (they cannot be used for our purposes, as they do not preserve the metadata). Therefore, we had to manually collect the data by using various websites' built-in export features. 

    - **Ethan, Yosef, and Nick** all equally worked to manually collect the data from baseball-reference.
    - **Yosef, Jason, and Ethan** all equally worked to manually/programmatically collect the data from chroniclingamerica.

- **Data Cleaning:** Additionally, these export features work quite poorly, exporting in inconsistent formats. So, we had to manually clean a lot of the data. Lastly, since the website only allows exporting (to CSV) of data one league and one year at a time, we had to figure out a way to combine the CSVs (with inconsistent variables, missing values, and inconsistent formatting) into one CSV, all while preserving each individual record's metadata. This process took many hours.

    - **Yosef, Ethan, and Kohta** worked to clean the data and write python scripts to combine the CSVs into one. This process can be seen, beginning in the "raw_data" folder, using the scripts in "scripts" folder, and the final product in the "combined_data" folder. 

- **Data Visualization:** worked together to create accurate, clean visualiztions displaying our data that we have collected and cleaned.

    - **Yosef, Kohta, and Ethan** worked to create graphs and models to display. saved in our "exploration_manipulation" and titled `metadata_over_time.ipynb`.
