# Bike Sharing
> Identifying which variables affect the business of a bike sharing company and to what extent.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This is a machine learning project trying to solve a business problem using Multiple Linear Regression model.
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
- So, the company wants to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
    - Which variables are significant in predicting the demand for shared bikes.
    - How well those variables describe the bike demands
- The dataset that is used for the project is 2 years of data (2018,2019) about different factors along with the numbers of bikes shared per day. The other factors include temperature, humidity, windspeed, etc on that particular day.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The final equation turned out to be: total_bikes_shared=(0.2323×year) − (0.0589×holiday) + (0.0469×workingday) + (0.5686×temp) − (0.1549×windspeed) − (0.2882×LightRainSnow) − (0.0828×Mist) + (0.0793×Summer) + (0.1281×Winter) − (0.0384×Jul) + (0.0904×Sep) + (0.0587×Monday) + 0.0817
- According to the equation, the factor that affecting the number of bikes shared in a day is temperature. As the temperature increases, the number of bikes shared tends to increase.
- We can also see the fact that a day being a Monday slightly affects the number of bikes shared.
- Factors like windspeed, Rain/Snow, Mist, etc affects the number of bikes shared negatively, i.e. increase in these variables will decrease the number of bikes shared on that day. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python Notebook
- Python 3
- library - sklearn
- library - statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Multiple Linear Regression.
- This project was based on [this tutorial](https://learn.upgrad.com/course/4476/segment/33701/199684/614616/3129221).


## Contact
Created by [@khyatidesai09](https://github.com/khyatidesai09) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->