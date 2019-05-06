
# FordGoBike Data Analysis 


## Introduction
The FordGoBike dataset of March 2019 contains 256,299 records.These records cotains information about individual trips taken in SanFrancisco. The dataset can be found [here](https://s3.amazonaws.com/fordgobike-data/index.html) 

## Data Analysis and Summary of Findings


Questions asked on this dataset:

- Which day is the most popular day for bike trip.
- Which type of user take rides more frequently.
- Which age group takes more number of rides.

start_date, member_birth_year, duration_sec and member_gender are the columns focussed on to answer above questions and draw conclusions.

Based on the analysis of data, following conclusions are drawn for each of the questions stated above.

- *Friday* is that weekday where people take most number of trips.
- *Subscriber* takes bike rides more frequently compared to that of *Customer*. But, *Customer* user type take trips for a longer duration with an average of ~27 minutes.
- Kids and Teens i.e people of age group *less than 20* take more number of rides.

## Insights for Presentation

Here, I tried to find the relation between the birth years and trip duration of 500 random samples collected from main dataset.
Then, gender variable is also added to find out if there is any dependency on trip duration.

- Most of the member_birth_years range between 1999 and 2019.
- *Male* gender take more number of rides.
- Mostly, trip duration range between 5 to 20 minutes.
- Average trip duration per gender is: Female - 14.61 minutes, Male - 12.31 minutes and Other - 17.58 minutes. Although 'Other'  gender has more average trip duration, it is mostly because of very few rides been taken for a longer duration. Hence, there is no direct relation between gender and how long the trip duration is.
