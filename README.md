# SOSurveysAnalysis

## Motivation
The goal of this project is to pose a number of business questions regarding the results of the StackOverflow surveys and answer them by means of the CRISP-DM method.
The following questions were asked:
1. Does the number of years coded professionally have an effect on how often people visit StackOverflow?
2. Are people who work remotely more satisfied by their job?
3. How does the popularity of different programming languages look like over the last three years?

## Results
After analyzing the data using CRISP-DM the answers to the questions posed are:
1. People who have been coding professionally for a longer period of time tend to visit StackOverflow less than people who are now getting their coding career underway or are new to coding professionally
2. Reading the survey results it could be said that there is a slight tendency that people who work remotely more frequently enjoy higher levels of job satisfaction
3. Python has seen a steady increase in its popularity in the last three years. On the other hand C# is less and less a part of developer's working life. JavaScript after an increase in popularity in 2018 compared to 2017, slightly declined in 2019, so that it is still more popular in 2019 compared to 2017.

## Libraries
The following python libraries are used:
- pandas
- numpy
- matplotlib

## Files
The following files are contained in this repository:
- README.md : The current file, which gives an overview of the project's motivation and structure
- notebook.ipynb : The notebook containing the analysis and its results
- developer_survey_2017.zip : Zip file containg the StackOverflow survey results from 2017
- developer_survey_2018.zip : Zip file containg the StackOverflow survey results from 2018
- developer_survey_2019.zip : Zip file containg the StackOverflow survey results from 2019

## Blog post
A Medium post describing the key takeaways and the motivation for this project can be found here:
https://medium.com/@kremmydosporos/is-working-remotely-going-to-make-you-happier-and-other-insights-from-stackoverflow-surveys-d333b6e0227a
    
## Acknowledgements
The survey data analyzed here were provided by StackOverflow (https://insights.stackoverflow.com/survey).

This project was developed as part of the Udacity Data Scientist Nanodegree.