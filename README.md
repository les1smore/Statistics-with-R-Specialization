# Statistics with R Specialization

## If you failed to open one project, please reload again.

### Project 1: "EDA_peer.html"

In this assignment, I was asked to imagine that I am a statistical consultant who has recently been hired by a real estate investment firm based in Ames, Iowa. They have had an intern collect and collate all of the recent house sales in Ames and have put together a large spreadsheet that contains the sale price of each house along with many of its physical features. My employers want me to take this data and develop a model to predict the selling price of a given home. They hope to use this information to help assess whether the asking price of a house is higher or lower than the true value of the house. If the home is undervalued, it may be a good investment for the firm.

My employers are savvy and have been successfully investing in real estate for a long time but they hope a more model-based approach will help focus their search, improving efficiency and the bottom line. The firm plans to use a combination of my model and industry professional expertise to make its investment decisions. Because of this, the firm is not willing to accept a black box solution - they have specified that they must be able to understand the details of my model, including its strengths and its weaknesses.

The goal of this assignment is to explore the data set that I will be using in my analysis of the housing market.

I will create some graphs to help me explore. I will also look at whether there are missing values in the variables. Finally, there will be a model selection section in which I will select a regression model. Here I used Backward Elimination method to select the best fit model.







### Project 2: "intro_data_prob_project.pdf"

Use the Behavioral Risk Factor Surveillance System (BRFSS) dataset to identify three research questions:
Research quesion 1: The relationship between female and their health quality.
Research quesion 2: The relationship between people’s employment status and their sleeping hours. 
Research quesion 3: The relationship between Internet and people’s exercise engagement.

Perform exploratory data analysis (EDA) that addresses each of the three research questions outlined above. 
This process contains numerical summaries and visualizations. 





### Project 3: "stat_inf_project.pdf"

Use the General Social Survey (GSS) dataset to identify a research question: The relationship between respondents’ education levels and their family income levels.

INFERENCE: Statistical inference via hypothesis testing and/or confidence interval.

State hypotheses
Check conditions
State the method(s) to be used and why and how
Perform inference
Interpret results
If applicable, state whether results from various methods agree





### Project 4: "reg_model_project.pdf"

Use the a movie dataset including information from Rotten Tomatoes and IMDB for a random sample of movies to complete exploratory data analysis (EDA), modeling, and prediction.
The data set is comprised of 651 randomly sampled movies produced and released before 2016.
Some of these variables are only there for informational purposes and do not make any sense to include in a statistical analysis. It is up to you to decide which variables are meaningful and which should be omitted. 
For example information in the the `actor1` through `actor5` variables was used to determine whether the movie casts an actor or actress who won a best actor or actress Oscar.





### Projct 5: "bayesian_project,pdf"

Use the same data set in Project 3, develop a Bayesian regression model to predict audience_score from the following explanatory variables.

This project consists of 6 parts:
1. Data: Describe how the observations in the sample are collected, and the implications of this data collection method on the scope of inference (generalizability / causality).

2. Data manipulation: Create new variables using the mutate function in the dplyr package following these guidelines:

Create new variable based on `title_type`: New variable should be called `feature_film` with levels yes (movies that are feature films) and no.
Create new variable based on `genre`: New variable should be called `drama` with levels yes (movies that are dramas) and no.
Create new variable based on `mpaa_rating`: New variable should be called `mpaa_rating_R` with levels yes (movies that are R rated) and no.
Create two new variables based on `thtr_rel_month`:
New variable called `oscar_season` with levels yes (if movie is released in November, October, or December) and no.
New variable called `summer_season` with levels yes (if movie is released in May, June, July, or August) and no.

3. EDA: Perform exploratory data analysis (EDA) of the relationship between audience_score and the new variables constructed in the previous part. 
This EDA process contains numerical summaries and visualizations. 

4. Modeling: Develop a Bayesian regression model to predict `audience_score` from the following explanatory variables.
Complete Bayesian model selection and report the final model. 
Also perform model diagnostics and interpret coefficients of the final model in context of the data.

5. Prediction: Pick a movie from 2016 (a new movie that is not in the sample) and do a prediction for this movie using the model developed and the `predict` function in R.

6. 6. Conclusion: A brief summary of the findings from the previous sections without repeating statements from earlier as well as a discussion of what learned about the data and research question. 
Discuss any shortcomings of the current study (either due to data collection or methodology) and include ideas for possible future research.

