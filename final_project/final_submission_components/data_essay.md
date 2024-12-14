# Group 5 Data Essay

- ### CONTENT: 
  - **Narrative - Nick & Yosef**
    - The project originally started as a research project into how statistics influenced sports betting on baseball. As the semester progressed, it was decided that this idea was way too one dimensional with little to no literature related to it. After this realization, Ethan suggested that we collect data from every league over the years to see the change of missing data sections and the differences of missing data sections and recording between the other major leagues that have appeared over time. With this new dataset created, It focused on batting and pitching statistics in addition to league team rankings from every ~5 years since 1871. This allowed us to visualize the difference in statistics and missing statistics between different years and different leagues through data manipulation. Although this was much better than trying to determine how statistics influences sports betting, it still was not enough. The last piece added to our databases was a collection of articles related to reporting on baseball leagues. This was done through Chronicling America and the API they have to gather articles related to baseball leagues.

  - **Methodology – Yosef**
    - Once the data was collected, we used various data manipulation tools to clean and prepare it for analysis, handling missing values, standardizing formats, and ensuring consistency across different time periods and leagues. We employed statistical imputation methods where appropriate but often had to leave gaps to maintain data integrity. For data analysis and visualization, we used Python and its data science libraries, including Pandas for data manipulation and Matplotlib and Seaborn for visualization. For newspaper data, we used Altair to create interactive graphs, which helped us visualize the frequency of mentions and other trends effectively. Throughout the project, team members collaborated extensively, especially during class time, to refine our methods and ensure the quality of our data. We continuously revisited our methodologies to maximize the informational value of our project, ensuring that our data was accurate, relevant, and informative. By employing these methodologies, we were able to efficiently gather, analyze, and visualize our data, providing a solid foundation for our project and its objectives.

  - **Statistic Historical Context - Jason**
    - This graph displays the average number of missing values of the statistics that we compiled from baseball reference. Beginning with the National League in 1876, and later followed by the American Association in 1882. During this time statistics were mainly kept by hand so missing values were likely due to scorekeepers not fulfilling their responsibilities. The missing values are also due to some statistics simply not being tracked during the time. For example, the statistics: stolen bases, caught stealing, grounded into double plays, sacrifice hits, sacrifice flies, intentional walks, and runners left on base were all not tracked in the beginning of the American Association. These stats gradually began to be introduced into the leagues culminating in 1955 when all stats were finally introduced and tracked.

  - **Publication Historical Context – Sam**
    - The historical context of this data is that it is a bunch of newspaper pages that we found that mention specific professional baseball leagues. Overall, collecting this data shows us the evolution of sports media and baseball leagues over time as well as the role that newspapers can play as historical records. To collect our data, Ethan created a function which allowed us to search the entire newspaper API for whenever each league was mentioned. This would then be compiled into a new document which would have every single page of the newspaper that mentioned this specific league. We would then do this for all of the leagues that we are looking at and compare the number of times the leagues are mentioned over time. Additionally, we would be able to make a heat map using Altair in order to visualize the statistics and make them clearer to read. Some difficulties that we encountered when doing this was that some leagues like the American league and the National league have thousands of pages which takes a lot of time to run. We also continued to run into timeout errors with the API since we were all running the code and it would return an error eventually for everyone which required us to stop and take a break. This meant that it would take even more time than was initially anticipated. Another issue that we encountered is that some phrases seemed to appear a lot more than we would have expected. One example of this was the American Association which showed up as having 5000 pages but was a league which only existed for a few years. This did not add up, but we were able to filter the API by year and made the results more accurate.

  - **Complexities – Jason & Nick**
    - We had statistics from a different website called baseball savant, but we were never able to add it. The statistics from baseball reference took extremely long to transfer into datasets because we had to manually add in the data points. As a result, we did not have enough time to work on all of the data points from baseball savant, and we do not believe that those data points were extremely relevant. A lot of data was gathered through Baseball References by hand which took a fairly long time to complete despite only gathering data from every 5 years instead of every year. Additionally, the data needed extensive cleaning to make it usable for our project.
---- 
- ### LABOR DIVISION
  - Data Gathering: Yosef, Ethan, Nick, Kohta
  - Data Analysis: Yosef, Ethan, Kohta
  - Statistics: Yosef, Ethan, Jason
  - Writing/Editing: Jason, Yosef, Kohta, Sam, Nick
---- 
- ### PURPOSE
  - **Potential Uses - Kohta**
    - *The datasets provided—batting statistics, detailed standings, and pitching metrics—have a variety of applications for scholarly research in sports analytics, history, and sociology. These datasets can be utilized in the following ways:*

    1. #### Sports Performance Analysis:
    - Researchers can use these datasets to analyze trends in team and player performance over time. For instance, batting and pitching data can be used to identify how game strategies have evolved, such as shifts in pitching effectiveness or batting power during different eras.
    - Relevant studies include Bradbury (2007), which examines the influence of performance metrics on team success (Bradbury, J. C. (2007). The Baseball Economist: The Real Game Exposed. New York: Dutton Books).

    2. #### Economic and Business Applications:
    - Data on team performance (e.g., wins, losses, and run differentials) can inform studies on the economics of sports leagues, such as the relationship between team success and attendance or revenue.
    - Scholarly works like Zimbalist (1992) on baseball economics could benefit from these datasets to refine models of financial performance in professional sports (Zimbalist, A. (1992). Baseball and Billions: A Probing Look Inside the Big Business of Our National Pastime. HarperCollins).

    3. #### Sociocultural Studies:
    - Historical data from different leagues, particularly with the inclusion of Negro League statistics, provide an opportunity to study the integration of sports and its cultural implications. This is especially relevant for examining racial integration in baseball as discussed by authors like Peterson (2002) (Peterson, R. M. (2002). Only the Ball Was White: A History of Legendary Black Players and All-Black Professional Teams.Oxford University Press).

    4. #### Predictive Modeling and Machine Learning:
    - The datasets are ideal for building predictive models in sports analytics, such as forecasting team success, player performance, or season outcomes. Applications include training machine learning models on historical data to predict future trends.

    5. #### Historical Comparisons:
    - Scholars interested in the history of sports can use the datasets to make comparisons between different time periods. For example, the impact of rule changes or significant events like World War II on league performance can be studied.

    - *By offering structured data that spans over a century, these datasets provide a foundation for multi-disciplinary studies, contributing to fields like sports management, economics, data science, and cultural studies.*

----

  - **Limitations and Considerations - Kohta**

  - *While these datasets offer significant potential, they also come with certain limitations and considerations that scholars must acknowledge:*

    1. #### Data Completeness and Quality:
    - Missing values are prevalent in certain columns, such as GDP, SH, and SF in the batting dataset or GBsum and vEast in the standings dataset. This could impact the accuracy of analyses.
    - Some entries have partial or inconsistent data, especially for historical records, reflecting the challenges of data collection in earlier eras.

    2. #### Historical Bias:
    - The datasets likely reflect biases inherent to the periods they cover. For example, data from the Negro Leagues may be less complete or systematically recorded compared to Major League Baseball, which can lead to disparities in analysis.
    - This limitation is discussed in academic literature, such as Burgos (2007), which highlights the challenges of reconstructing Negro League histories ([Burgos Jr., A. (2007). Playing America's Game: Baseball, Latinos, and the Color Line. University of California Press]).

    3. #### Lack of Contextual Data:
    - The datasets focus solely on performance metrics and lack contextual information, such as team finances, player injuries, or societal events, which might influence the data.

    4. #### Privacy Concerns:
    - Although historical data generally falls outside privacy regulations, users should exercise caution if attempting to integrate these datasets with modern datasets involving personal identifiers.

    5. #### Barriers to Reuse:
    - The technical format of the datasets may pose challenges for less experienced researchers. Providing code for common analyses (e.g., R or Python scripts) could enhance usability.
    - Accessibility issues, such as requiring domain knowledge to interpret certain metrics, should also be considered.

    6. #### Temporal Scope and Relevance:
    - While the datasets span a broad temporal range, modern applications (e.g., predictive modeling for today’s games) may find the older data less relevant due to shifts in play style and rules.

    - *By understanding these limitations, future users can make informed decisions about how to best utilize the datasets while mitigating potential issues.*
