# Amazon_Vine_Analysis

## Project Overview

This project was to determine if vine reviews (a paid program) caused a product to sell better on Amazon or if the sales were indifferent. Several different applications were utilized to accomplish this analysis. Pyspark within Google Colab was used to perform an ETL process on the dataset. The data came from an Amazon web service and was extracted into datframes for transformation, in Google Colab.  And an RDS databse was created to hold the massive amount of data to be parsed through. After the transformation of the data was completed, which included filtering and new dataframes, the filtered data was extracted into PostgreSQL as tables.  One last set of scripts were written and run to filter further.  

## Results

The process and analysis resulted in illustrating the following information.  
  - The amount of Vine and non-Vine reviews - 
 
 Vine
 Those with vine reviews is 22.  
 ![71AE2767-67AC-4D3A-8853-1BB6C5460BD9](https://user-images.githubusercontent.com/96222437/163726277-dc0636e7-a6e2-4a98-ac15-30562c185985.jpeg)

 
 
 Non-Vine
 The amount of reviews that didn't have a vine process on them is 26,987.
 
 ![6590F4A3-E371-484A-BEC9-4C8CAE2EBDDA](https://user-images.githubusercontent.com/96222437/163726282-8e9efbef-e673-419e-8b28-e605c5306775.jpeg)



How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

The amount of reviews with 5 stars is over 14,488 , as seen below.  

![A2F8C6DD-B370-438D-8308-13FA394EA4A5](https://user-images.githubusercontent.com/96222437/163726430-5d3dee42-d8d3-409b-a212-88f08a8365c5.jpeg)

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
The percentage of vine reviews is .15%
The percentage of non-vine reviews is 86%

![09D4EF51-8A44-4CCA-B22D-9AFFAC65361F](https://user-images.githubusercontent.com/96222437/163726532-6e8585d9-13ed-4ff0-8545-06d6e840226f.jpeg)


## Summary

The vine paid program does not seem to have an impact on the reviews.  There are far more reviews with 5 stars that did not have the vine payment.  The large percentage of the data frame shows that the good ratings fall outside of the vine program.  
An additional analysis I would perform would be to determine a percentage of the amount of sales for products with or without the vine program.  
