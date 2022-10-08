# Linear-Regression-Assignment

# Project Name
> ## Bike Sharing Assignment



## Table of Contents
* [Problem Statement](#problem-statement)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)



## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. A US bike-sharing provider ***BoomBikes*** has decided to come up with a mindful business plan to be able to accelerate its revenue. In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

The company wants to know:

    - Which variables are significant in predicting the demand for shared bikes.
    - How well those variables describe the bike demands

## Business Goal

Model the demand for shared bikes with the available independent variables. The model will be used by the management to understand how exactly the demands vary with different features. The business strategy can be manipulate accordingly to meet the demand levels and meet the customer's expectations. The model will be a good way for management to understand the demand dynamics of a new market. 


## Technologies Used
- ***Python*** - version ***3.x***
- ***pandas*** - version ***1.4.2***
- ***numpy*** - version ***1.21.5***
- ***matplotlib*** - version ***3.5.1***
- ***seaborn*** - version ***0.11.2***
- ***sklearn*** - version ***1.0.2***
- ***statsmodels*** - version ***0.13.2***


## Conclusions

As per the final Model, the top 3 predictor variables that influences the bike booking are:

- Temperature (temp) - A coefficient value of ‘5514’ indicated that a unit increase in temp variable increases the bike hire numbers by 5514 units.

- Year (year) - A coefficient value of ‘0.2388’ indicated that a unit increase in year variable increases the bike hire numbers by 0.2388 units.

- Wind Speed (windspeed) - A coefficient value of ‘-0.1838’ indicated that, w.r.t windspeed, a unit increase in windspeed variable decreases the bike hire numbers by 0.1838 units.
