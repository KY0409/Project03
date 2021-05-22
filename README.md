# STA9760 S2021 Project03 Streaming Finance Data with AWS Lambda
In this project, we are going to utilize the following Amazon aws technologies to process and analyze real-time stock price on 05/11/2021 for 10 companies at a 5 minute interval, processing the data and then dumping it in a manner that facilitates querying and further analysis, either in real time or near real time capacity.


## AWS tool used

###
1. AWS Lambda and layer
2. AWS Kinesis Stream(Data Stream and Delivery Stream)
3. AWS S3 bucket
4. AWS Glue 
5. AWS Athena to query data 

Step I: Lambda Function(DataTransformer)


Create a Lambda function which containes yfinance that gathers our stock price data 

Step II: Kinesis (DataCollector)
Create a Kinesis stream that holds our data

Step3: Athena(DataAnalyzer)

Configure AWS Glue to point to the S3 bucket which allow us to interatively query the highest hourly stock “high” per company 




## Configs
![kinesis_config](https://github.com/KY0409/Project2/blob/main/cluster_configuration.png)
![s3_bucket](https://github.com/KY0409/Project2/blob/main/notebook_configuration.png)
