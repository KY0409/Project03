# Project03 Streaming Finance Data with AWS Lambda
In this project, we are going to utilize the Amazon aws technologies to process and analyze real-time data,processing the data and then dumping it in a manner that facilitates querying and further analysis, either in real time or near real time capacity.


## AWS tool used

AWS Lambda
AWS Kinesis Stream(Data Stream and Delivery Stream)
AWS S3 bucket
AWS Glue and Crawler
AWS Athena to query data 

Step I: Lambda Function(DataTransformer)


Create a Lambda function that gathers our data 

Step II: Kinesis (DataCollector)
Create a Kinesis stream that holds our data

Step3: Athena(DataAnalyzer)

Configure AWS Glue to point to the S3 bucket which allow us to interatively query the S3 files .




## Cluster and Notebook Configs
![cluster](https://github.com/KY0409/Project2/blob/main/cluster_configuration.png)
![notebook](https://github.com/KY0409/Project2/blob/main/notebook_configuration.png)
