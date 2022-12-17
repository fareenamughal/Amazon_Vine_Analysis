# Amazon Vine Analysis
Module 17:Big Data - PYSPARK, Amazon Web Services (AWS), Relational Database Services (RDS), Google Collab and pgAdmin  
___

## Overview of the analysis of the Vine program
___
Amazon product review for various shoe brands was extracted from the web, transformed and loaded using Pyspark in google collab and Relational Database Services (RDS) offerred by Amazon Web Services(AWS) This was followed by loading the data into pgAdmin via AWS-RDS. pgAdmin made it easier to transform the data into tables which were then downloaded into seperate coma seperated files (CSV). The csv files, particurlarly the vine_table csv was loaded int jupyter notebook to run pandas code so as to prepare an analyse of the customer reviews received for the various shoe brands. This report focuses on the customer reviews and the purpose is to determine whether there is any bias toward favorable reviews from Vine members who have provided reviews in the shoes dataset.

___

## Results
___

The results of the Vine Review Analysis can be found as per screen shot image and code below:
1.	The code is in the jupyter notebook as per link below  
[Vine Review Analysis]( https://github.com/fareenamughal/Amazon_Vine_Analysis/blob/63d3881c688e7b45103e73a9560ffaceae0c4041/VIne_Review_Analysis.ipynb)




There is a bulleted list that addresses the three questions for unpaid and paid program reviews (7 pt)
Results: Using bulleted lists and images of DataFrames as support, address the following questions:

How many Vine reviews and non-Vine reviews were there?
How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?


___

## Summary:

Based on the analysis, the paid 5 star reviews as a percentage of the total paid reviews was 59 as compared to 54 percent for the unpaid reviews. This, on face value, seeems to suggest highly biased reviews. However, on further analysis it is clear that the total paid reviews as a percentage of the total helpful reviews is less than 0.1%. The paid five star % i.e. 59 is actually 59% of the 0.1% which is an immaterial number. In conclusion the results of the vine review analysis indicate that reviews are not biased.






Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

![Revised NYC Citibike csv](https://github.com/fareenamughal/bikesharing/blob/5082e0ac1987257a5e8bb1d4bd9399a949494e53/Images/screenshot_nyc_citibike_rev_csv_file.png)

![image](https://user-images.githubusercontent.com/112118706/208268200-37ed105a-3e39-4a87-95c2-a680e9077440.png)
