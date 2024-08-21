Cloud Data Modeling Repo:  

This repository provides End to End projects for data analysis and machine learning modeling using Amazon Web Services and Microsoft Azure.  


## Overview of data modelling with Amazon Web Services (AWS):  

**ML modelling of Bank Marketing with SageMaker at AWS**  
-- Dataset was taken from kaggle and cleaned for all categorical variable and null values.  
https://www.kaggle.com/datasets/henriqueyamahata/bank-marketing    
-- notebook instance at AWS Sage maker was used for ML modlelling, dataset was downloaded insidse the instance. 
-- S3 bucket was created,train and test data was stored inside the S3 bucket  
--Xgboost image model was created and model training was performed with help of sagemaker.estimator.  
-- model deployed and used for prediction of test data set.   
-- notebook is available (AWS-ML-MarketingProject.ipynb)    