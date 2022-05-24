# MVP-2022-Predictions

[Link to Full Notebook with PlotlyVisualizations](https://nbviewer.org/github/Drewsky33/MVP-2022-Predictions/blob/main/MachineLearning/Predictions%20%281%29.ipynb)

## Project Overview

This project uses Machine Learning to predict who would win the 2021-2022 NBA MVP Award. We know that Nikola Jokic won the award, but I wanted to see if computers would make the same predictions and which variables factored most into the computer's decisions. This project utilized web scraping, data cleaning, and machine learning to make the final predictions. There are also some components of data visualization with the plotly library. 

### Project Workflow

- Scrape data from [Basketball Reference](https://www.basketball-reference.com/) through the help of [DataQuest WebScraping Tutorials](https://www.youtube.com/c/Dataquestio).
- Data cleaning, table aggregating, and feature engineering. 
- Exploratory Data Analysis
- Data Cleaning for Regression analysis
- Building customized performance metrics for model predictions. 
- Utilizing backtesting to optimize model performance
- Data Visualization to explore model biases
- Trying an alternative model to Ridge Regression, Random Forest Regressor comparison. 

### Code

The code for this project can be found here:

[Link to Full Notebook with PlotlyVisualizations](https://nbviewer.org/github/Drewsky33/MVP-2022-Predictions/blob/main/MachineLearning/Predictions%20%281%29.ipynb)


### Data

[Data Scraped](https://github.com/Drewsky33/MVP-2022-Predictions/tree/main/Data)

[Data Cleaning Notebook](https://github.com/Drewsky33/MVP-2022-Predictions/tree/main/Cleaning)

### Project Questions
- Is Nikola Jokic the MVP in the eyes of computers?
- How is the Ridge Regression Model biased?
- Which statistics are most important in predicting MVP vote shares?
- Who was the real MVP?

## Project Highlights

### Scraping Data

<img width="1002" alt="image" src="https://user-images.githubusercontent.com/77873198/170119826-09923f88-d488-40ee-b8cc-d19271e43841.png">

### Cleaning Data/Merging Tables/Exploring Correlations
<img width="876" alt="image" src="https://user-images.githubusercontent.com/77873198/170120334-21b7525a-12c7-48f6-9b0e-7440942da870.png">


### Model Building
<img width="823" alt="image" src="https://user-images.githubusercontent.com/77873198/170121605-12ef60d7-3870-418b-a819-d219dd3306cb.png">

### Data Visualization
<img width="1067" alt="image" src="https://user-images.githubusercontent.com/77873198/170121063-4239c02a-f0d1-4797-910a-4ef322989b34.png">

Interactive visualizations can be viewed [here:] https://nbviewer.org/github/Drewsky33/MVP-2022-Predictions/blob/main/MachineLearning/Predictions%20%281%29.ipynb

### Performance:
<img width="1093" alt="image" src="https://user-images.githubusercontent.com/77873198/170121846-c5088603-11b6-4d9c-b3c5-25f3a1bcc395.png">

## Conclusions
- Our algorithm actually predicted that Giannis Antentokounmpo was the 2022 NBA MVP.
- The Ridge Regression model we created outperformed the Random Forest model slightly.
- Both models were in the 70% accurate range for predicting a player's MVP vote shares.
- The models were highly biased towards points scored and wins in their predictions. While the predictions were strong, we could improve them further by incorporating advanced defensive metrics so that more value is placed on more defensively-minded players.

## What I learned
- I learned how to scrape and clean data from [Basketball Reference](https://www.basketball-reference.com/)
- Create customized metrics for regression models by taking into account different parts of the data. 
- Improve model performance through backtesting.
- Creating ratio metrics based off of existing columns in the dataset to provide more information (feature engineering).
- Drilling down into model biases through advanced data visulization.

### Resources
- [DataQuest YouTube Channel](https://www.youtube.com/c/Dataquestio) for web-scraping and model-building
- [Plotly](https://plotly.com/python/horizontal-bar-charts/#configure-horizontal-bar-chart) for data viz
