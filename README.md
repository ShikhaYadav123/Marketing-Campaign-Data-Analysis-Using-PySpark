# Marketing-Campaign-Data-Analysis-Using-PySpark
#Requirement:  Load ad_campaigns_data.json, user_profile_data.json and store_data.json files in HDFS. 
Write PySpark code in Jupyter notebook to solve below mentioned analytical problems. 
Q1. Analyse data for each campaign_id, date, hour, os_type & value to get all the events with counts
Q2.Analyse data for each campaign_id, date, hour, store_name & value to get all the
events with counts
Q3.Analyse data for each campaign_id, date, hour, gender_type & value to get all the
events with counts


Store processed json data of each problem statement into different HDFS output directory. Once output data is available into HDFS, create external Hive tables on top of it using Json Serde
