
# Investigation of No-Show Medical Appointments

> Project submission for Udacity Data Analyst Nano Degree Program

## Table of Contents
<ul>
<li><a href="#intro">Introduction</a></li>
<li><a href="#conclusion">Conclusion</a></li>
</ul>


<a id='intro'></a>
## Introduction

The dataset under investigation is a collection of information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment.Various characteristics about the patient are included such as Gender and Age as well as each individual's primary health designation(s) such as Hypertension, Alcoholism, and Diabetes. 

The dataset was originally sourced from <a href="https://www.kaggle.com/joniarroba/noshowappointments" target="_blank">Kaggle</a>. 
Udacity's version of the dataset (which this analysis has been conducted on) can be downloaded <a href="https://www.google.com/url?q=https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd2e9a_noshowappointments-kagglev2-may-2016/noshowappointments-kagglev2-may-2016.csv&sa=D&ust=1513377859161000&usg=AFQjCNELJtHRQ9r28kGlBHv9nIUVIMalkQ" target="_blank">here</a>. 


<a id='conclusion'></a>
## Conclusion

Nearly 80% of all appointments investigated were no-shows. This number was the root driver of the analysis. The following conclusions were drawn to serve as a basis for a more robust analysis in the future.

#### Findings and Future recommendations:

_What is the breakdown of no-shows versus shows by patients that received SMS reminders_

* Sending an SMS reminder to patients doesn't seem to increase the number of patients showing up for their appointment. But it would be worth performing additional regression analysis to understand how strong this correlation is.

_What is the patient health designation breakdown of no-shows versus shows_

* None of the health condition increases or decreases the probability to show up at the appointment time. One reason could be that these health conditions are such that they might sometimes need an urgent care rather than visiting their healthcare provider on a set appointment date in the future.

_Which neighborhoods have the highest number of no-shows_

* "JARDIM CAMBURI" neighbourhood had more number of "No-Shows". It would be worth analyzing further on how this neighbourhood is making sure patients turn up for their appointments.

_Do appointment no-shows occur on specific days of the week_

* Weekdays had more number of "No-Shows" compared to on weekends, especially during first 3 days of the week. It's difficult to draw any conclusions from this but could be run through a regression analysis to better understand which other show rate influencer day of week correlates with.

#### Limitations:

* Data for a longer timeframe could provide insight into how seasonality and holidays impact show rates.

* Combining external data sources such as traffic, weather, or geographic data with this dataset could put in light some of the other factors that influence patients to not show up.

* Further analysis of patients with repeat no-shows could also bring in some other information which influence them to repeatedly miss their appointments
