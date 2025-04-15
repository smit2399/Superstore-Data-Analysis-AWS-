 **Superstore Data Analysis (AWS)**

---

This project establishes a pipeline to analyze Superstore sales data, utilizing the powerful capabilities of AWS. It transforms the data to ensure it is ready for thorough exploration. By executing SQL queries on the transformed data, we reveal important trends and patterns. The results are then analysed and presented through clear and accessible visualisations, offering valuable insights into Superstore sales performance.

**AWS services used**

\- IAM   
\- S3  
\- AWS Glue  
\- AWS Athena  
\- AWS QuickSight

![Superstore DA Architecture drawio](https://github.com/user-attachments/assets/01436457-27be-4059-a93e-c5ab1e6c15ca)


1. **IAM (Identity and Access Management):**   
   Establishing an IAM user that specifies permissions for users and applications to access and control data in various services such as S3, Glue, Athena, and QuickSight.

2. **S3 (Simple Storage Service):**   
   The S3 Bucket acts as the storage location for data where unprocessed data is uploaded prior to processing. I established various folders to assist the Crawler with Partitioning.

3.  **AWS Glue:**   
   ETL (extract, transform, and load) data is aided by glue. Establishing a data catalogue by executing a crawler.

4.  **AWS Athena:** 

Athena provides querying of the converted data stored in S3 via Glue.  
It aided in running SQL queries.

5. **Amazon QuickSight:**

QuickSight facilitates the creation of data-driven visualisations and dashboards.  
It employed Athena's data analysis results to create data visualisations. 

**Snapshots**

![Quicksight-report_page-0004](https://github.com/user-attachments/assets/7c93d0e1-f735-4690-941c-012e59a6ba7e)

![Quicksight-report_page-0005](https://github.com/user-attachments/assets/7f5d272a-763f-4a98-9f00-3b9ee8997210)

![image 7](https://github.com/user-attachments/assets/0ee9ee61-e8b8-47a1-9f92-7a43e4bde3c8)
  
