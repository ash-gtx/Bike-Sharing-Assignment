# Bike Sharing Assignment

## **Problem Statement**

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

**Business Goal**:

You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

**Issues to Address:**

1. **Revenue Decline:** BoomBikes faces substantial revenue declines due to the ongoing pandemic, necessitating a strategic solution.
2. **Market Sustainability:** The company struggles to sustain itself in the current market scenario, demanding a mindful business plan.
3. **Post-Lockdown Strategy:** BoomBikes aims to accelerate revenue post-lockdown, requiring an understanding of post-quarantine bike demand.

**Objectives:**
The objectives include predicting significant variables influencing American market shared bike demand, determining the crucial predictors, developing a model to understand demand variations, facilitating adaptive business strategies, and exploring demand dynamics for effective decision-making. This case study aims to achieve this goal by building a multivariate linear regression model using the provided  dataset day.csv (attached in github)

The primary objective is to identify the key variables that significantly influence the prediction of shared bike demand and assess how effectively these variables describe the patterns in bike demands.



## Conclusions

- The equation of the best fit line is given by:
  - **_cnt_** = 0.13 + 0.23 x **_yr_** - 0.09 x **_holiday_** + 0.51 x **_temp_** - 0.14 x **_windspeed_** + 0.10 x **_summer_** + 0.13 x **_winter_** - 0.08 x **_mist_and_clouds_** - 0.28 x **_stormy_condition_** + 0.05 x **_August_** + 0.11 x **_September_**
- Bike rental booking demand is influenced by **yr**, **holiday**, **temp**, **mist_and_clouds**, **windspeed**, **Summer**, **Winter**, **September**, **stormy_condition** and **August**
- Out of these, key features are **temp**, **yr** , **winter**
-  Upon completion of Model building we see that Training model was showing 83.4% variance and our test case shows 79.3%. The difference is relatively small < 5% and can be said that model's performance in test cases is still resonably good.¶



## Technologies Used
- Pandas 
- Numpy
- Matplotlib 
- Seaborn
- Statsmodels
- SKlearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by live session of upGrad on Industry Relevance of Linear Regression Models.
- UpGrad tutorials on Linear Regression on the learning platform


## Contact
Created by [@ash-gtx] - feel free to contact me!
