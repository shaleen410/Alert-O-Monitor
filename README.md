# Alert-O-Monitor
“Alert-O-Monitor” is a one-stop solution for managing end-to-end flow of Early Warning Signals.
We are not only focusing on “Alert Generation”, but we are also doing “Alert Monitoring”, “Alert Resolution” as well as “Alert Prediction” giving a complete 360-degree comprehensive solution which NONE of the Banks have implemented till now. 

# Data Engineering
1. Create Microsoft Lakehouse named AOM_Lakehouse.
2. Under the Data Engineering folder, we have Raw Files sub-folder which has all the raw-data files and these files can be uploaded into the lakehouse files and create tables on top of it.
3.  Under the Data Engineering folder, we have Lookup Files sub-folder which has all the loop-up files and these files can be uploaded into the lakehouse files and create tables on top of it.
4.  Once the Tables are created, Pick up all the notebooks from the Data Engineering folder.
5.  Run all the notebooks(note: main notebook needs to be run at the end).

# Data Science 
1.  Under the Data Science folder, two notebooks named loan_prediction_new and product_recommendations can be run.
2.  For the voice analytics notebook, we have a pre-requisite that 

# Data Modeling
1. Create a new semantic model on top of the lakehouse.
2. Create the relationships as shown in below.
![Screenshot (11)](https://github.com/shaleen410/Alert-O-Monitor/assets/160255203/04b3dcbe-e8e2-4b3c-a16d-6d11f2e4007e)

![Screenshot (12)](https://github.com/shaleen410/Alert-O-Monitor/assets/160255203/4e8312bf-d4aa-49b7-98bd-75fa186f4b10)

# Data Analysis
1. We create a powerBI report on the lakehouse that we have created.
2. Under the Data Analysis folder, we have the powerbi report uploaded use it and re-point to the lakehouse that is created.
3.This is how the power bi report looks as shown below:
 ![image](https://github.com/shaleen410/Alert-O-Monitor/assets/160255203/0129ec6f-2f84-44d3-8e20-e47a70887686)





   
