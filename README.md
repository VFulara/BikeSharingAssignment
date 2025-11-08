# Bike sharing system demand analysis
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. A US bike-sharing provider BoomBikes aspires to understand the demand for shared bikes among the people
Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Project Contains the bike-sharing data in days.csv file.
- The bike-sharing company Boom bikes wants to predict the demand of bikes to improve their business decisions
- Project attempts to find parameters impacting the demand most
- As an outcome a model is also created which predicts the demand, also some model evaluation criterias are also explored

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- At a high level demand seems to have string correaltion with temp, atemp, register/casual in quantitative variables
- Various categorical variables like season2, specific months and weather situation seems to have direct impact on demand
- Top 3 contributing features are atemp, casual and season 2
- Attribute 'yr' (2018/2019) also has a good impact on demand

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- statsmodel
- pandas
- seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by upgrad assignment



## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->