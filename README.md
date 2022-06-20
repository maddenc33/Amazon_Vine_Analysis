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
There is a huge bias in the data set I chose, which was reviews for digital video games.  In my data set there were no vine reviews at all!  In order to perform an additional analysis on the data set, we should choose a different data set.  I have succeeded in proving that this data set of reviews will not provide us with the information we are looking for.
