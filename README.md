# Amazon Vine Analysis
Module 17:Big Data - PYSPARK, Amazon Web Services (AWS), Relational Database Services (RDS), Google Collab and pgAdmin  
___

## Overview of the analysis of the Vine program
___
Amazon product review for various shoe brands was extracted from the web, transformed and loaded using Pyspark in google collab and Relational Database Services (RDS) offerred by Amazon Web Services(AWS) This was followed by loading the data into pgAdmin via AWS-RDS. pgAdmin made it easier to transform the data into tables which were then downloaded into seperate coma seperated files (CSV). The csv files, particurlarly the vine_table csv was loaded int jupyter notebook to run pandas code so as to prepare an analysis of the customer reviews received for the various shoe brands. This report focuses on the customer reviews and the purpose is to determine whether there is any bias toward favorable reviews from Vine members who have provided reviews in the shoes dataset.

___

## Results
___

The results of the Vine Review Analysis can be found as per workings/code in jupyter notebook and screen shot image below:
A.	The code is in the jupyter notebook as per link below  
[Vine Review Analysis](https://github.com/fareenamughal/Amazon_Vine_Analysis/blob/e2969ebdbdb0a006a33f47d4bdcb041815554a6d/VIne_Review_Analysis.ipynb)

B. The screenshot of the results of running the analysis as per jupyter notebook. 

### **Vine Review Analysis Summary**

![Vine Review Analysis Summary](https://github.com/fareenamughal/Amazon_Vine_Analysis/blob/e3b5d5f6a68fb391bc722a0250988404df9d4591/Resources/images/Vine_Review_Analysis_Summary.png)

This summary answers the 3 questions below:
1. How many Vine reviews and non-Vine reviews were there?
   - The Vine reviews are identified by the letter Y and non-Vine reviews by letter N. There were 44 Vine reviews and 53,978 non-Vine reviews    

2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?  
   - Out of the 44 Vine reviews 26 were five star reviews whereas out of the 53,974 non-Vine reviews 28,950 were five star reviews

3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
    - 59% of the Vine reviews were five star whilst 54% of the non-Vine reviews were five star. Please note these percentages are based as a proportion       of the total vine reviews and non-Vine reviews respectively. They are not based as a percentage of the total helpful reviews.

___

## Summary:

Based on the analysis, the paid 5 star reviews as a percentage of the total paid reviews was 59% as compared to 54% for the unpaid reviews. This, on face value, seeems to suggest highly biased reviews. However, on further analysis it is clear that the total paid reviews as a percentage of the total helpful reviews is less than 0.1%. The paid five star reviews of 59%, is actually 59% of the 0.1% which is an immaterial number, approximately 0.5%. Whilst the unpaid-Vine five star reviews are 54% of 99.91% In conclusion, the results of the vine review analysis indicate that reviews are not biased.

The additional workings supporting this analysis are as per screenshot below.
![Additional workings](https://github.com/fareenamughal/Amazon_Vine_Analysis/blob/fd16fbea59fd0123c7aa714e5dc3ba37addc89c5/Resources/images/Additional%20workings.png)




