# Amazon_vine_Analysis
# Overview of the Analysis:
The main purpose of this project is to analyze the amazon reviews written by members of the paid amazon vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. In this analysis we are using Pyspark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.
# Results:
#### [Vine Reviews](https://drive.google.com/file/d/1vct9eQJkMiShVIHf_H9AOPll7EuOXbqt/view?usp=sharing):
- The total number of vine reviews is 1266.
- Vine reviews with 5-star rating are 432.
- The percentage of 5-star vine reviews is 34.12.
#### [Non-vine Reviews](https://drive.google.com/file/d/15k1wrN78OXpuk-IgkJUPAQeUqyPW0JYd/view?usp=sharing):
- Number of non-vine reviews is  62028.
- Non-vine reviews with 5-star rating are 29982.
- Lastly, the percentage of non-vine reviews with a 5-star rating is 48.34.
# Summary:
The number of unpaid-vine reviews is much higher than the paid vine reviews program. Therefore, the bias is towards un-paid vine reviews. Furthermore, we can analyze whether the review purchase is verified or non-verified.



