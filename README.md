# Amazon Vine Analysis

## Overview

For this project, we are asked to analyze reviews from a chosen dataset. PySpark was used to perform the ETL process. The data was extracted, transformed and loaded into pgAdmin. PySpark was used again to determine if there was any bias from Vine members.

## Results

- How many Vine reviews and non-Vine reviews were there?

<img width="758" alt=" unpaid_vote" src="https://user-images.githubusercontent.com/100614930/175850994-858e4cab-e8bc-4f04-b8fc-21cb74464373.png">

There was 37,840 non-vine reviews

![paid_vote](/images/paid_vote.png)

There was 170 Vine reviews

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

![5_star_paid](/images/5_star_paid.png)

There were 65 Vine reviews that were 5 star

![5_star_unpaid](/images/5_star_unpaid.png)

There were 20,612 non-Vine reviews that were 5 star

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
