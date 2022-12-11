# Regression Assignment: Bike Sharing

>The objective is to model the demand for shared bikes
with the available independent variables. It will be used by the management
to understand how exactly the demands vary with different features. They can
accordingly manipulate the business strategy to meet the demand levels and
meet the customer's expectations. Further, the model will be a good way for
management to understand the demand dynamics of a new market. 
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands


## Table of Contents
* [About Boom Bikes](#about-boom-bikes)
* [Summary](#summary)
* [Technologies Used](#technologies-used)
* [Contact](#contact)


<!-- You can include any other section that is pertinent to your problem -->

## About Boom Bikes
- A bike-sharing system in which bikes are made available for shared use to individuals on a short term basis
for a price or free. It allow people to borrow a bike from a "dock" which is usually computer-controlled
wherein the user enters the payment information, and the system unlocks it. This bike can then be returned
to another dock belonging to the same system.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Summary
- After comparing results between train and test data, the trained model can able to generalize the unseen data very well with only consideration of 8 variables
- Top 3 predictor variables that influences the bike booking:
  - atemp: A unit increase in feeling temp variable, increases the bike rides by 0.378637 units.
  - weathersit_3: A unit increase in weathersit_3 variable, increases the bike rides by 0.284695 units.
        - weathersit_3: (Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds)
  - yr_2019: A unit increase in yr_2019 variable, increases the bike rides by 0.253157 units.
- It is suggested to consider these variables utmost importance while planning, to achive maximum Booking
- In Jan and Feb we can suggest to service the bikes, with out much impacting the business

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Language: Python
- Libraries: Pandas, Numpy, Seaborn, Matplotlib, Sklearn
- IDE: Jupyter Notebook

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by https://www.linkedin.com/in/mmveereshkumar - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
