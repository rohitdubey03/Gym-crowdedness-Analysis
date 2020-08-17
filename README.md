# -Gym-crowdedness-Analysis
Python notebook using data from Crowdedness at the Campus Gym (kaagle)


# About this Dataset


## Background

When is my university campus gym least crowded, so I know when to work out? We measured how many people were in this gym once every 10 minutes over the last year. We want to be able to predict how crowded the gym will be in the future.

## Goals

Given a time of day (and maybe some other features, including weather), predict how crowded the gym will be.
Figure out which features are actually important, which are redundant, and what features could be added to make the predictions more accurate.

## Data

The dataset consists of 26,000 people counts (about every 10 minutes) over the last year. In addition, I gathered extra info including weather and semester-specific information that might affect how crowded it is. The label is the number of people, which I'd like to predict given some subset of the features.

## Label:

Number of people
Features:

date (string; datetime of data)

timestamp (int; number of seconds since beginning of day)

day_of_week (int; 0 [monday] - 6 [sunday])

is_weekend (int; 0 or 1) [boolean, if 1, it's either saturday or sunday, otherwise 0]

is_holiday (int; 0 or 1) [boolean, if 1 it's a federal holiday, 0 otherwise]

temperature (float; degrees fahrenheit)

is_start_of_semester (int; 0 or 1) [boolean, if 1 it's the beginning of a school semester, 0 otherwise]

month (int; 1 [jan] - 12 [dec])

hour (int; 0 - 23)



### Acknowledgements

This data was collected with the consent of the university and the gym in question.

### Article

https://rohitdubey03.github.io/gymEda.html

