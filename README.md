# Bike-Sharing-Case-Study
## Problem Statement:

> A US bike-sharing provider **BoomBikes** has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain itself in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


The company wants to know:

-   Which variables are significant in predicting the demand for shared bikes?
-   How well do those variables describe the bike demands?


## Business Goal:
> Business Goal is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short-term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

#### day.csv
-   This is the dataset which is used to build the LR model to drive the inferences.

#### Data-Dictionary.txt
-   This file consists description of variables and their meaning explaining the dataset of (day.csv file).

#### Linear-Regression-Subjective-Questions.pdf
-   It contains the question and answers to the subjective questions.
    


## Conclusions
- Seasons: There is a high demand for bikes in the season of `fall` and `summer`.
- Year: The year 2019 was highly demanding as compared to the year 2018.
- Months: Demand is high in the months of August, September, and October and low in January.
- Weekday/Holidays/Weekend: Weekend and holidays day have high demand.
- Weathersit: 
    -   High demand with - "Clear, Few clouds".
    -   Low demand with "Light Snow, Light Rain"
- Top variable towards explaining the demand for bike sharing:
    -   yemp: It has a high correlation with cnt
    -   yr: It has a positive correlation with cnt
    -   mnth: August, September and October have a positive correlation with cnt



## Technologies Used
- python - version 3.9.1
- numpy - version 1.21.5
- matplotlib - version 3.5.2
- seaborn - version 0.11.2
- scikit-learn - version 1.0.2
- statsmodels - version 0.13.2
- missingno - version 0.5.1
- pendulum - version 2.1.2
- jupyter notebook - version 6.5.1



## Acknowledgements
Give credit here.
- This project was inspired by Upgrad and IIIT Bangalore
- Upgrad course learning content, live session and Google search.


## Contact
Created by Ranjit Patra [@ranjitpatra](https://github.com/ranjitpatra) - feel free to contact me!
