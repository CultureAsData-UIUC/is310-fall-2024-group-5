# Instructor Feedback on Experimenting with Datasets Update

## General Comments

Overall, I'm pleased with your progress with this update and glad to see that you are largely collaborating together. I thought your `README.md` file was very helpful, though it was a bit confusing that your assignment was in the `pivoted_group_project` folder so I would recommend potentially renaming the folder to be more descriptive. I thought the division of labor was very helpful, and I appreciated the detailed documentation on what had been added to the dataset, as well as its utilities. I thought the consideration of the strengths and weaknesses of the dataset was very helpful, and largely I agree with your assessments––so well done! 

- appreciate the readme though the name of the folder is a bit confusing for the assignment. Also found it confusing that you have a scripts folder filed with Jupyter notebooks
- Liked the detailed documentation on what had been added to the dataset, as well as its utilities
- especially Appreciate the consideration of the strengths and weaknesses of the dataset, and agree with your assessments, though you might consider if scholars in the humanities would find the dataset useful
- finally division of labor was very detailed and excellent inclusion

## Specific Feedback

### Scripts Folder

The code in the scripts folder appears to work well, though it is a bit confusing that rather than scripts the folder contains Jupyter notebooks. I do think you could combine that code into a script if that's what you are planning. Regardless, the code seems to focus primarily on data cleaning, which is great, but additional documentation would be helpful to clarify what each notebook is doing and how it fits into the overall workflow.

### Metadata Over Time Notebook

This notebook seems to be the core of your project and contains some strong analyses. While the notebook is functional, it could benefit from clearer organization and more detailed interpretation of the results. I appreciated your efforts to note who contributed what materials, as it’s not easy to collaborate on the same notebook—good effort there!

In terms of the computational methods, the quality varies depending on whether I assess based on the due date of the assignment or the most recent commits. Yosef appears to have led much of the data analysis, with contributions from Nick as well. The visualization of missing values over time was useful, though normalizing it to total values over time could provide better insights into the proportion of missing data. Expanding to multiple leagues and including interactive visualizations were also strong contributions.

More recent commits introduced additional code, which is great progress! The exploration of missing data subsets was particularly interesting. I recommend further investigating potential correlations between missing entries, time, and the datasets you’ve compiled to determine whether the gaps are due to historical errors or specific patterns related to certain statistics or leagues. 

I was particularly impressed with the addition of the *Chronicling America* data. It seems like Ethan lead the charge on this aspect and the analysis of coverage over time by league and newspaper was especially fascinating—great work there, especially on the interactive visualizations!

I did notice some errors in the code, including repeated imports of libraries. Cleaning up the code and streamlining it—such as choosing one plotting library (either Matplotlib or Altair) for consistency—would greatly improve readability and efficiency.

## For Final Project Submission

For your final project submission, I recommend focusing on streamlining your code and organizing your notebooks more clearly to ensure they’re easy to follow. I also recommend including your thoughtful reflections on the dataset’s strengths, weaknesses, and utility for different audiences—such as humanities scholars—will also add valuable context.

Additionally, you might consider synthesizing your analyses into a cohesive narrative that ties your findings together. Highlighting key trends, such as coverage differences over time or by league, and connecting these insights to the broader goals of your project will strengthen your final submission. Finally, incorporating some of the peer-reviewed scholarship from the *Computing Cultural Data* assignment would also provide a solid foundation for your dataset’s interpretation and use.

Overall, you’re in a strong place for your final submission, and I’m excited to see how everything comes together—keep up the great work!