<h1>Group 5 -- Computing Cultural Data</h1>

<h2>Section One -- Computational Methods and Cultural Data Types</h2>

Yosef:
- A computational method is a systematic approach or algorithm that processes data through mathematical and logical operations using computers.
- A cultural data type refers to any form of data that captures or represents cultural expressions, practices, or artifacts.

<h3>Computational Methods</h3>
<ul>
  <li>Time Series Regression Analysis</li>
    <ul>
      <li>A method for examining historical data to identify patterns over time.</li>
    </ul>
  <li>Predictive Modeling
    <ul>
      <li>A method uses past data to predict future results.</li>
    <ul>
</ul>

<h3>Cultural Data Types</h3>
<ul>
    <li>Gambling Records</li>
        <ul>
            <li> Records and statistics regarding rates of gambling, specifically in baseball</li>
        </ul>
    <li>Baseball Statistics</li>
        <ul>
            <li>Team and player statistics in baseball.</li>
        <ul>
</ul>


<h3>Time Series Regression Analysis and Gambling Records</h3>
<ul>
    <li>First, I found an article written by <a href="https://www.gla.ac.uk/schools/socialpolitical/staff/heatherwardle/">Heather Wardle</a>, a social scientist with over twenty years of experience in the field, leading the British Gambling Prevalence Survey and co-director of Gambling Research Glasgow. She specializes in understanding how technological infrastructure creates risks and opportunities regarding gambling behaviors.
    TO BE FINISHED. https://www.ncbi.nlm.nih.gov/books/NBK576910/</li>
</ul>

# Baseball Physics Analysis with Computational Modeling and Cultural Data
Kohta

## 1. Selected Computational Method: Predictive Modeling
- **Method Description**: Predictive modeling is a machine learning approach used to forecast future outcomes based on historical data. Techniques such as regression, decision trees, and neural networks are common, but in this context, we’ll focus on regression modeling.
- **Application to Baseball**: Predictive modeling in baseball can forecast outcomes like game scores or player performance. By analyzing variables like past game stats, player conditions, and team compositions, these models make predictions on who might win a game, how a player’s season might unfold, or even fan attendance trends.
- **Cultural Relevance**: Predictive modeling captures baseball's strategic depth, aligning with cultural narratives around the skill and unpredictability of sports. It reflects an analytical view of baseball, where data and probability intersect with tradition, showing how past performances shape expectations and narratives around future games.

## 2. Selected Data Type: Player Performance Data
- **Data Type Description**: Player performance data includes measurable stats such as batting averages, strike rates, on-base percentages, fielding accuracy, and pitching velocity. This quantitative data is collected consistently throughout seasons and serves as a record of individual and team skill levels.
- **Importance in Cultural Analysis**: This data type reflects baseball's meritocratic nature, where players gain recognition based on their performance. Tracking these statistics over time allows for analysis of broader societal trends, such as the rising role of fitness, strategy, and the adoption of sports science. This data also contributes to the culture of fandom and hero worship, as fans follow star players and teams closely, often correlating their success to their own regional pride or identity.

## 3. Example Research Question and Application
- **How Can Predictive Modeling Be Used to Forecast a Player’s Season Performance?**
  - **Application**: Using historical player performance data, a regression model could predict individual players' seasonal batting averages or the likelihood of achieving certain milestones (e.g., a set number of home runs). This approach could integrate additional data such as player fitness levels or historical performance under similar conditions.
  - **Cultural Insight**: The model illustrates baseball as a blend of skill, data, and tradition. It highlights society’s appreciation for statistical milestones and achievements, reflecting how data-driven forecasting can deepen public engagement and understanding of the sport. 


# 
Nick  

## Bibliographic Information
Bayesian models for prediction of the set-difference in volleyball  
Authors: Ioannis Ntzoufras, Vasilis Palaskas, Sotiris Drikos  
Publish Date: November 11th, 2019  
https://stat.paperswithcode.com/paper/bayesian-models-for-prediction-of-the-set  

## Method / Data Description
Bayesian analysis is a type of statistical method that applies Bayes' theorem to update the probability of a prediction as more data becomes available. Bayes' theorem is a mathematical formula used to predict conditional probabilities. Bayesian analysis will take in the current data and make predictions for stats in our case and continue to update them as new data is produced from new games.  

It shows prior probability of the data we currently have, the likelihood of certain things happening giving the current data, and post-addtional data probability after recieving new data.  

For gambling, Bayesian analysis is commonly used for forecasting / risk assesment and decision-making under uncertainty. This can help gamblers decide on who and what they bet on.  

Code is available here:  
https://github.com/Vasilis-Palaskas/Bayesian-Models-for-Prediction-of-the-Set-Difference-in-Volleyball  

## Argument in Scholarship
Main Argument: The project I found was attempting to create a Bayesian analysis model for volleyball as you cannot use the more standard match outcome calculations due to its outcomes being decided by a set-difference compared to goals or points scored in soccer or football. 

Method Usage: Introduced two model types to analyze volleyball set differences: an ordered multinomial logistic regression model and a tailored version of the Skellam distribution which is typically used for other sports. The modified Skellam model was changed to count by sets for volleyball. Both models are evaluated though a Bayesian framework paired with Markov Chain Monte Carlo (MCMC) simulations for predictions.  

## Interesting Point / Argument for Our Project
Baye's theorem isnt that complicated but provides bountiful information from it. Especially when you pair with an additional prediction modeling system like the MCMC simulations.  

Being able to take our current data and create current predictions and keep the predictions accurate by adding additional data into the predictions is very useful for sports data that people like to bet on. This would provide a better of an educated guess than a person just picking purely off historic stats. We would be attempting to forecast the future stats of a player compared to just guessing.  

#
Jason

## Bibliographic Information 
Article Title: Explorations in Baseball Analytics: Simulations, Predictions, and
Evaluations for Games and Players
Publisher: University of Wisconsin Milwaukee
Author: Katelyn Mongerson
Publish Date: May 2023
https://dc.uwm.edu/cgi/viewcontent.cgi?article=4197&context=etd 

## Method / Data Description
This article describes how baseball statistics have grown throughout the years and presents five different predictive simulations/models that predict future results.
The first coding simulation is called a Run Expectancy Matrix. The purpose of it is to improve decision making from a baseball team. It uses past results to show the expected runs(runs is what points are called in baseball) based on the current situation of the game. The author uses this example in the article, "For example, when there is a runner on first with 1 out, the average team would score .51 runs by the end of the inning." This number was found by taking the average number runs scored in an inning after this situation occurs. Baseball teams can use this to know what positions to put their team in for the best results, this can work if they are the team batting, or the team playing defense.

The next simulation is called The Nine Player Monte Carlo Simulation. This simulation works by taking data from a team's particular seasons meaning all of their hits, errors, walks, and strikeouts; it then runs this data through simulation which can be ran as many times as you want, and calculates the average number runs per game that team would score with those statistics. The author uses an example of the statistics from the Milwaukee Brewers during the 2022 season. She simulated their average runs per game 10,000 times and it returned that the Brewers average runs per game 4.66 which was very close to their actual number of runs per game that season with 4.48.

The other three simulations were a little more complicated to describe for people that are not baseball savants, so I will keep my analysis to these two simulations.

## Argument in Scholarship
The article works to present how baseball can be statistically analyzed using coding simulations. The author compares real-life results and results of the simulations to show how accurate the predictions are. 

## Interesting Point
This article taught me many ways to use statistics as a way of predicting future results. It can be useful for managers of baseball teams to look at, to assess the performance of players and use their players' statistics to predict if the team will be successful. I would categorize this as Computational Data Science in the sports field.

We can use these models as a basis for what can be created using baseball statistics. We can also alter these models and imporve them to create more accurate predictions. The author describes different way that these simulations could be improved in the Future Work section of her paper.