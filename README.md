# Bike Sharing Assignment
> Bike Sharing Assignment tends to identify the factors affecting the demand for these shared bikes in the American market 


## Table of Contents
* [Problem statement and Goal](#general-information)
* [Overview of Data Analysis Approach](#technologies-used)
* [Summary of Analysis](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic finding it hard to sustain .
- Company aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.
- Goal : Identify the factors affecting the demand for these shared bikes in the American market 
- Dataset : day.csv

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Based on Model analysis, below variables are significant . Some variables will impact in positive way while some other will have negative impact 
- Temp, Windspeed, yr, spring, misty, jul, sep, sat, wet

Bike demand is impacted positively with below variables,
- yr - As it is a new concept, YoY there seems to be an increase and can fairly assume higher demands in current year.
- temp - increases with slight higher temps in US so may be launched in cities which has acceptable temps throughout the year .
- Bike Demand is slightly higher in Sep Month and during Saturday in a week .

Bike Demand is impacted negatively with below variables
- Bike Demand is less during high wind speed .
- Bike Demand is less in Spring : This may be due to the Dataset as we saw in Boxplot that during Spring time the Demand curve slowly increased from first half to Second half . Please refer to Box plot - seasons V/s cnt w.r.t year
- Bike Demand is less in Misty and Wet weather conditions basically about to rain or rainy sessions

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Anaconda3 jupyter Notebook
- python 3.9

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- Thanks to Upgrad Instructors and Live Sessions


## Contact
Created by [@skmdesai] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
