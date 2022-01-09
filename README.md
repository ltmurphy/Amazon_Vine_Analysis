# Amazon_Vine_Analysis

## Overview

### In this analysis, a group of datasets containing reviews from Amazon Vine members is presented. One of the data sets is chosen and is processed using ETL methods. The resulting data is connected to an AWS RDS database and the transformed data is loaded into pgAdmin. Then, using PySpark, the analyisis is examined for bias in the reviews.

## Results

### The final results show the Vine reviews:


![total_vine_reviews](https://user-images.githubusercontent.com/89947873/148702870-53492bbf-00b0-4988-a188-741f52008d95.png)


### and the non-Vine reviews:


![total_non-vine_reviews](https://user-images.githubusercontent.com/89947873/148702896-18607423-2c57-47cc-ae79-8776f3edf346.png)


### 5-star Vine reviews:


![vine_5-star_reviews](https://user-images.githubusercontent.com/89947873/148703011-f43f3d67-1c8f-4a2f-83ff-83ebae8b4d97.png)


### 5-star non-Vine reviews:


![non-vine_5-star_reviews](https://user-images.githubusercontent.com/89947873/148703029-89bd1fc9-6c5a-472f-8d8f-2da612a6114a.png)


### Percentage of 5-star Vine reviews:


![percentage_5-star_Vine](https://user-images.githubusercontent.com/89947873/148703195-3feafb69-3645-4fc4-a64b-fd300cbca257.png)


### Percentage of 5-star non-Vine reviews:


![percentage_5-star_non-Vine](https://user-images.githubusercontent.com/89947873/148703199-7dd5ecea-1ce9-43d3-bef5-9c377ad6c533.png)


## Summary
### The results indicate a slight positivity bias in the Vine reviews versus the non-Vine reviews. This is highlighted by forty-six five star Vine reviews compared to the thirty-one five star non-Vine reviews. However, this is not necessarily the truest view of the data. Analysing the data to see which purchases are verified versus non-verified would provide a more complete picture. Verified purchases are purchased from Amazon at full price. Non-verified purchases are not purchased from Amazon or are purchased at a discount.
