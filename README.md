# NYC High School SAT Scores - Data Exploration, Visualization, & Analysis

As a native New Yorker who was educated in the public school system, I have always been curious about the diverse ethnic background of the student population. 

The goal of this project is to explore a set of data related to the Scholastic Aptitude Test, or more commonly known as the SAT. Are there clear patterns or observations in the data that can possibly explain how student performance can be determined? 

This is also an opportunity to practice with data cleaning and the various visual packages that the MatPlot library and Seaborn have to offer. 

<p align = "center">
  <img src="https://2aih25gkk2pi65s8wfa8kzvi-wpengine.netdna-ssl.com/blog/files/2018/08/shutterstock_1027883017.jpg" width=420 height=280 />

## The Dataset

The dataset is retrieved from New York City Department of Education and can be found on the [Kaggle](https://www.kaggle.com/nycopendata/high-schools) website. 

## Insights & Observations

<p align="center">
  <img src = "https://github.com/eric8395/Eric_Portfolio/blob/main/images/SAT%20Scores.png" width="600" height="450">
  </p>
  
There are many highschools with a low percentage of the Asian and White student population (less than 10%). These schools appear to also have lower average SAT scores and are generally clustered together. However, there appears to be a slight positive relationship between percentage of White and Asian students as the percentage of ethnicities increases.

Comparitively, there is less of a clusttering of data points for percentage of Black and Hispanic students in high schools. The data points are generally spread evenly across the percentage spectrum and display a slight negative relationship.

There are several positively correlated relationships:

* Total Average Score Against Student Enrollment

* Total Average Score Against Percent Asian

* Total Average Score Against Percent White

* Student Enrollment Against Percent Asian

* Student Enrollment Against Percent White

These relationships can also explain why SAT scores for Black and Hispanic students are lower as there is a negative relationship associated with these variables. Schools with a low student enrollment tend to have lower SAT scores. 

# What does the NYC public high school demographic consist of? 
* The total white student enrollment in NYC High Schools is 40601
* The total black student enrollment in NYC High Schools is 85020
* The total hispanic student enrollment in NYC High Schools is 118539
* The total asian student enrollment in NYC High Schools is 50955
* The total other student enrollment in NYC High Schools is 5494

These numbers provide us some idea but let's better visualize the student demographic with a pie chart.
<p align="center">
  <img src = "https://github.com/eric8395/nycsatscores/blob/main/images/Screen%20Shot%202022-01-01%20at%206.11.41%20PM.png?raw=true" width="600" height="450">
  </p>
  
The borough of Manhattan sees the greatest percentage of students tested at about 70% with Queens closely behind. The Bronx sees the least percentage of students tested at about 55%. 
<p align="center">
  <img src = "https://github.com/eric8395/nycsatscores/blob/main/images/Screen%20Shot%202022-01-01%20at%206.13.33%20PM.png?raw=true" width="570" height="320">
  </p>

