# Amazon_Vine_Analysis

#### by Christopher Madden

## Overview
Create an AWS RDS database with tables in pgAdmin, pick a dataset from the Amazon Review datasets, and extract the dataset into a DataFrame. 
Determine if there is any bias towards reviews that were written as part of the Vine program, to see if having a paid Vine review makes a difference in the percentage of 5-star reviews.

## Results
![Img1](https://github.com/maddenc33/Amazon_Vine_Analysis/blob/main/Images/Img1.png?raw=true)
![Img2](https://github.com/maddenc33/Amazon_Vine_Analysis/blob/main/Images/Img2.png?raw=true)
- How many Vine reviews and non-Vine reviews were there?
  - 0 Vine reviews
  - 1,685 non-Vine reviews
- How many Vine reviews were 5 stars?
  - 0
- How many non-Vine reviews were 5 stars?
  - 631
- What percentage of Vine reviews were 5 stars?
  - 0
- What percentage of non-Vine reviews were 5 stars?
  - 37.4%

## Summary
There is no way of determining whether a bias exists in the data set I chose, Amazon reviews for digital video games.  In my data set there were no vine reviews at all!  We cannot perform any additional analysis on this data set with regards to comparing Vine and non-Vine reviews.  I have succeeded in proving that this data set of reviews will not provide us with the information we are looking for, which is often the case in analytics.
