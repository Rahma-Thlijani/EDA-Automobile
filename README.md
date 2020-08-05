![Image](car1.jpg)
# EDA-Automobile-Prediction
Data science project, in which we apply: Exploratory Data Analysis, Data Visualization, Feature Selection, and Deep learning model aiming to predict a car price.
## Data Description
We have two datasets in this project: "StatsVideosXALL.csv" (for the features) and "StatsVideosXALL.csv" (for the output).
The datasets has 3365 rows and 4 columns: Likes, Dislikes, Subscribers and Views, they are related to each youtube video. 
## Project Overview
In this data science project, we will focus on applying an **exploratory data analysis, visualizing the data, and selecting the features**. In addition, we will train a deep learning model aiming to predict the price of the car regarding its different properties. Finally, we will evaluate the model based on the MAE
the RMSE and the R2_Score.
## Project Steps
You will first understand the data the we will apply data exploration. Afterwards, we will train two different models and finally we will evaluate them.
All the project steps are organized and listed below:

### 1. Data Import
### 2. Data Understanding and Manipulation
* Show data header
* Show columns names
* Drop the first irrelevant column
* Fix columns names
* Data information
* Check to number of rows and columns
### 3. Data Processing
* Dealing with missing data
* Drop the duplicate rows
* Correct data format
* Dealing with outliers
* Data standardization
* Data normalization
* Binning
* Converting categorical values
### 4. Exploratory Data Analysis
* Descriptive Statical Analysis 
* Analyzing Individual Features 
* Combinaison and Groupping 
* Output Analysis
### 5. Feature Selection
### 6. Model Development
* Select the dataframe
* Split data set into training and testing parts (80/20)
* Scale both training and testing input data
* Train the regression model
### 7. Model Evaluation
## Conclusion / Results
We tested the deep neural network model on the testset to provide predictions, and the we evaluated its performance using the three metrics:
* Mean Absolute Error (MAE): 12317109.74
* Root mean squared error (RMSE): 56406118.44
* R-squared Score (R2_Score): 0.8038
