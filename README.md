Cloud Data Modeling Repo:  

This repository provides End to End projects for data analysis and machine learning modeling using Amazon Web Services and Microsoft Azure.  


## Overview of ETL data pipeline with Amazon Web Services (AWS):  
**ETL pipeline of spotify dataset**    
-- Dataset was taken from kaggle:  
 https://www.kaggle.com/datasets/tonygordonjr/spotify-dataset-2023  
-- Create IAM user and access to different sources  
-- Create S3 bucket and store the raw data  
-- Create data pipeline with AWS glue: join different tables, drop some columns and store transform data in the target location  
-- Create data catalog, database and tables with crawler  
-- Create AWS Thena and setup Query editor to make Query  
-- Create Quicksight to create visualization and publish it as dashboard  
-- detailed information about each step as described in ETLProject-Spotify.txt file  
 

## Overview of data modelling with Amazon Web Services (AWS):  
**ML modelling of Bank Marketing with SageMaker**  
-- Dataset was taken from kaggle and cleaned for all categorical variable and null values.  
https://www.kaggle.com/datasets/henriqueyamahata/bank-marketing    
-- notebook instance at AWS Sage maker was used for ML modlelling, dataset was downloaded insidse the instance. 
-- S3 bucket was created,train and test data was stored inside the S3 bucket  
--Xgboost image model was created and model training was performed with help of sagemaker.estimator.  
-- model deployed and used for prediction of test data set.   
-- notebook is available (AWS-ML-MarketingProject.ipynb)    


## Overview of ETL pipeline for time series data analysis using AWS:        
**ETL pipeline of time series dataset**        
-- Dataset of superstore was taken from kaggle:     
https://www.kaggle.com/datasets/vivek468/superstore-dataset-final     
-- Create S3 bucket and store partitioned daily data     
-- Create crawler for partitioned data    
-- Create data pipeline to convert csv or existing database to Another format like json format with help of AWS Glue,Visual ETL.      
-- AWS Triggers to schedule initiating an ETL job.     
-- detailed information about each step as described in ETL-TimeseriesProject.txt file      


## Overview of PySpark DataFrame and Glue DynamicFrame for data analysis using AWS:    
**Data Frame of customer dataset**       
-- Dataset was taken from this link:   
https://github.com/johnny-chivers/sql-for-athena/tree/main/data     
-- Upload SparkDataFrame-Project.ipynb Notebook to AWS Glue notebook  
-- Create GlueContext and spark_session    
-- Use GLUE SQL to manipulate the data    
-- Work with Spark Data Frame and Glue Dynamic Frame    