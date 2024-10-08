# Data Reflection and Documentation

## Documenting The Data

### Dataset Structure

Our dataset consists of the following columns:

1. Rk (Rank): Integer
2. Player: String
3. Year: Integer
4. xwOBA: Float
5. BA - xBA: Float
6. Avg EV (MPH): Float
7. LA Sweet-Spot %: Float
8. Barrel%: Float
9. Hard Hit %: Float
10. EV50: Float
11. Adjusted EV: Float
12. Whiff %: Float
13. Swing %: Float
14. Like Player (added subjective column): Boolean

### Data Quality and Completeness

The data appears to be complete for all 24 players listed, with no missing values. The quality seems high as it comes from an official MLB statistics platform (Baseball Savant). The added subjective column "Like Player" is complete but based on personal opinions.

### Dataset Location

The collected and curated dataset can be found in the `proprietary-perspectival-dataset-creation` folder of our repository, named `player_stats_2024.csv`.

## Reflecting on The Data

### Subjective Column Creation

We decided to add a "Like Player" column as our subjective measure. This column represents whether each group member likes the player or not. We chose this because:

1. It's highly subjective and can lead to interesting discussions within the group.
2. It allows us to explore how personal preferences might influence data interpretation in sports analytics.
3. It adds a human element to otherwise purely statistical data.

There were some discrepancies in how group members interpreted this column. Some based their likes on statistical performance, while others considered factors like the player's personality or team affiliation.

### Data Collection Process

We collected data from Baseball Savant (https://baseballsavant.mlb.com/), focusing on the 2024 season's batting statistics. We chose this data because:

1. It provides advanced metrics that are relevant to modern baseball analysis.
2. It offers a good mix of traditional and new-age statistics.

The main difficulty in collecting this data was ensuring we didn't violate MLB's terms of service. We manually copied the data to avoid any potential issues with scraping or bulk downloads.

### Platform Dynamics

This dataset captures several important dynamics in baseball:

1. The shift towards data-driven decision making in baseball, as evidenced by the advanced metrics included.
2. The growing importance of exit velocity and launch angle in evaluating hitters.
3. The balance between contact ability (low Whiff %) and power (high Barrel %).

However, the dataset doesn't capture:

1. In-game situational performance
2. Player injuries or time missed
3. Team dynamics or chemistry
4. Off-field factors that might influence performance

### Legal and Ethical Considerations

1. Data ownership: MLB owns this data, and their terms of service restrict commercial use without permission.
2. Privacy concerns: While this data is publicly available, continuous collection and analysis of player performance data could raise privacy issues.
3. Potential for misuse: Advanced statistics could be used to create betting algorithms, which might be against MLB's wishes.
4. Bias in subjective data: Our added "Like Player" column introduces personal bias, which could skew analysis if not properly contextualized.

These considerations could impact future research by:
- Limiting the ability to freely share or distribute the dataset
- Requiring researchers to obtain explicit permission from MLB for certain types of analysis
- Necessitating clear separation between objective and subjective data points in analysis

## Licensing The Data

Given the proprietary nature of the MLB data, we cannot apply an open license to the entire dataset. However, for our added "Like Player" column, we choose to apply a Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) license.

This license allows others to use and build upon our subjective data for non-commercial purposes, as long as they give appropriate credit.

### Additional Reuse Considerations

1. The MLB statistical data should not be reused without permission from MLB.
2. Our "Like Player" column can be freely reused under the CC BY-NC 4.0 license, but users should be aware of its subjective nature.
3. Any reuse should clearly distinguish between the official MLB statistics and our added subjective data.
4. Researchers should be transparent about the source of the data and any modifications made.
5. Consider the potential impact of personal biases when using the "Like Player" column in analysis.

