# Amazon_Vine_Analysis

## Analysis Overview

Evaluation of the Amazon Vine program for video game reviews. There are reviews by paid subscrivers to the vine program and by non-subscribers. The below analysis shows comparisons of both paid and unpaid reviewers.

## Results

Pulling in the data and creating separate DataFrames allowed for a more detailed analysis of the reviews. To derive this analysis, multiple filtered DataFrames were created. The first was total_votes coutn >= 20.

![image](https://user-images.githubusercontent.com/90691846/148698033-5aa9c804-bc91-41c7-9d3a-b48e747f92e6.png)

The DataFrame was then filtered to show rows where the number of helpful_votes were divided by total_votes >= 50%.

![image](https://user-images.githubusercontent.com/90691846/148698082-0a015ce1-a286-4d1b-a97a-715e891c90a1.png)

The below analysis was filtered off of the DataFrame above.

### Vine Reviews

- There were a total of 94 paid reviews
- There were a total of 48 5-star paid reviews
- Roughly 51% of the paid reviews were 5-star reviews
 
![image](https://user-images.githubusercontent.com/90691846/148698360-75a59d93-b18d-48da-8137-5d7fbd781ee5.png)

### non-Vine Reviews

- There were a total of 40,471 unpaid reviews
- There were a total of 15,663 5-star unpaid reviews
- Roughly 39% of the unpaid reviews were 5-star reviews

![image](https://user-images.githubusercontent.com/90691846/148698244-4cccc77e-2cea-4700-8caa-c8b4d872db1e.png)

## Summary

In comparison of the unpaid versus paid reviews, it appears there is a slight bias for the paid subscribers since there is a 12% variance between the percentages. Another way to determine bias outside of the percentages would be to analyze the statistics of each i.e., median, mean, standard deviation.

