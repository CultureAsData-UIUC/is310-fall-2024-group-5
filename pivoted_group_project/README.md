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


## Dataset Utility

By combining records from different sources, leagues, and eras, we can observe differences in how data was recorded and kept between leagues and over time.

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
- The dataset includes the missing_value_count whichc allow future users to see any areas that may need t be excluded or reworked for future analysis

Weaknesses:
- Missing things like Mexican Baseball League (LMB) and likely other leagues' stats as they are not available on baseball reference
- Data was taken every 5 years but there are likley leagues that existed for less than that time
- Data collection started in 1871 and leagues could have existed before then
- The dataset does not have contextual factors such as rule changes or other events that have changed teh game significantly
- There is no player level stats to do in depth individual analysis

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

    - **Ethan, Nick, and Yosef** all equally worked to manually collect the data.

- **Data Cleaning:** Additionally, these export features work quite poorly, exporting in inconsistent formats. So, we had to manually clean a lot of the data. Lastly, since the website only allows exporting (to CSV) of data one league and one year at a time, we had to figure out a way to combine the CSVs (with inconsistent variables, missing values, and inconsistent formatting) into one CSV, all while preserving each individual record's metadata. This process took many hours.

    - **Ethan, Yosef, and Kohta** worked to clean the data and write python scripts to combine the CSVs into one. This process can be seen, beginning in the "raw_data" folder, using the scripts in "scripts" folder, and the final product in the "combined_data" folder. 

- **Data Visualization:** (TO BE COMPLETED)