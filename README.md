# Hive-HDFS
**Learning Hive and HDFS**
- SQL-Like Queries (HiveQL): Hive uses HiveQL, a query language similar to SQL, making it easier for data analysts and stakeholders to query and analyze the data without requiring deep knowledge of Hadoop-specific tools.
- Integration with Hadoop: Hive integrates seamlessly with Hadoop Distributed File System (HDFS), allowing for the efficient storage and analysis of large datasets across multiple nodes. This integration ensures optimal performance when working with high volumes of data.

**Sources Database:**
Source
Kaggle dataset (Healthcare database)

Details
Includes information on 10,000 patients from 8,639 hospitals, covering patient demographics, medical conditions, treatment histories, hospital visit records, insurance claims, and financial data totaling 255.17 million in hospital payments. Key areas of focus are patient distribution, billing analysis, and healthcare trends.

Dataset Link
https://www.kaggle.com/datasets/prasad22/healthcare-dataset


1. Upload the file using WinSCP
<img width="1010" height="606" alt="Syot layar 2025-07-04 224202" src="https://github.com/user-attachments/assets/526b17c5-4814-4840-82be-be2aa89cc0ae" />
2. Create an HDFS Directory and Upload the File
3. Upload the CSV File to HDFS
4. Connect to Hive Using Beeline
5. Switch to Database and List Existing Tables
6. Create an External Table for Datahealthcare.csv
7. Verify Table Creation 
