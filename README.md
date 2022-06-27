# Amazon Vine Analysis

## Overview

For this project, we are asked to analyze reviews from a chosen dataset. PySpark was used to perform the ETL process. The data was extracted, transformed and loaded into pgAdmin. PySpark was used again to determine if there was any bias from Vine members.

## Results

- How many Vine reviews and non-Vine reviews were there?

<img width="758" alt=" unpaid_vote" src="https://user-images.githubusercontent.com/100614930/175850994-858e4cab-e8bc-4f04-b8fc-21cb74464373.png">

There was 37,840 non-Vine reviews

![paid_vote](/images/paid_vote.png)

There was 170 Vine reviews


- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

![5_star_paid](/images/5_star_paid.png)

There were 65 Vine reviews that were 5 star

![5_star_unpaid](/images/5_star_unpaid.png)

There were 20,612 non-Vine reviews that were 5 star


- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

![percent_paid](/images/percent_paid.png)

38% of Vine reviews were 5 star

![percent_unpaid](/images/percent_unpaid.png)

54% of non-Vine reviews were 5 star


## Summary

According to the results, there is no suggestion that there is a bias among Vine members in the review. There seems to be an opposite effect, wherein non-Vine members have a higher percentage of 5 star reviews. However, there is a large gap between the total number of reviews between the Vine and non-Vine members. Vine members only represent 170 reviews, while non-Vine members make up over 37,000 reviews. This may suggest bias in the data as the percentage and counts can change if the Vine reviews and non-Vine reviews were more similar in the number of reviews. I would include all the votes to see if the data changes since there was some filtering done on the votes to clean the data.
