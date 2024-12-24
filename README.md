# Project Name
> BoomBikes, Buike sharing Linear Regression project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Problem Statement
BoomBikes, a US-based bike-sharing provider, has faced a significant revenue decline due to the COVID-19 pandemic. To recover and prepare for post-pandemic demand, the company aims to analyze factors influencing shared bike usage. 

### Business Goals:

- Model the demand for shared bikes using available independent variables.
- Enable management to understand how demands vary with different features.
- Support management in adjusting business strategies to meet demand levels and customer expectations.
- Provide insights into demand dynamics for potential entry into new markets.

## Solution Approach:

I intend to build the model by adhering to the below process:  
1. Importing the data, understanding, and visulaizing the data
    - This will help to understand the data distribution and see how the variables are correlated
2. Data preparation for model building
    - Convert the categorical variables into 0/1
    - Scale the variables value
    - creating train data/test data
3. Use RFE to get the top variables and build the model, if required optimize further.
4. Residual Analysis to ensure model is robust.
5. Predict the values on test data and calculating the value of R-square

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1. The of bike users have incressed significanly, positive coefficient shows that the business is likely to grow in coming years.
2. The user count is highly dependent on Temprature.
3. Wind speed & Light rains does impact the business.
4. The bike user is positively correlated with wokring day.
5. But Boom bike can run some dicsounted offers during holidays to grow their business.

The R² scores for the training set (82.9%) and the test set (80.1%) suggest that your linear regression model performs reasonably well. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas
- Numpy
- Sckitlearn
- Matplotlib
- Seaborn
- statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was based on my learning AIML Upgrad PGDM Course.


## Contact
Created by [@kushbajpai] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->