# Insurance Premium Prediction

## Problem Statement :
This project's all about figuring out what you're likely to pay for health insurance, based on your own health situation. Once you've got that estimate, you can go ahead and pick any health insurance company you like, and choose from the plans they've got, with our cost prediction in your back pocket. It's a way to help you focus on the health coverage you need and skip over the stuff that doesn't do much for you.

## Dataset :
The dataset is taken from a Kaggle. You can download the dataset from [here](https://www.kaggle.com/noordeen/insurance-premium-prediction)

## Approach :
So, we're using a bunch of cool machine learning techniques to solve a problem. We'll start by digging into the data, cleaning it up, picking out the important bits, and then actually building a model. Once that's done, we'll test it to make sure it works right. The end goal is to create something that can guess how much you'll have to pay for your health insurance premium.

- **Data Exploration :** Exploring the dataset using pandas, numpy, matplotlib, plotly and seaborn.
- **Exploratory Data Analysis :** Plotted different graphs to get more insights about dependent and independent variables/features.
- **Feature Engineering :** Numerical features scaled down and Categorical features encoded.
- **Model Building :** In this step, first dataset Splitting is done. After that model is trained on different Machine Learning Algorithms such as:
    1) Linear Regression
    2) Decision Tree Regressor
    3) Random Forest Regressor
    4) Gradient Boosting Regressor
    5) XGBoost Regressor
    6) KNN
- **Model Selection :** Tested all the models to check the RMSE & R-squared.
- **Pickle File** : Selected model as per best RMSE score & R-squared and created pickle file using pickle library.
- **Webpage &Deployment :** Created a web application that takes all the necessary inputs from the user & shows the output. Then deployed project on the Heroku Platform.


## Deployment Link :
https://insurance-premium-prediction1.herokuapp.com/


## Web Inerface :
![alt text](https://github.com/nikhilpatil44/insurance-premium-prediction/blob/main/images/webapp%20interface-2.png)



## Libraries used :
    1) Pandas
    2) Numpy
    3) Matplotlib, Seaborn, Plotly
    4) Scikit-Learn
    5) Flask
    6) HTML
    7) CSS

## Technical Aspects :
    1) Python 
    2) Front-end : HTML, CSS
    3) Back-end : Flask
    4) Deployment : Heruko

