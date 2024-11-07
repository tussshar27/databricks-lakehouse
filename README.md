# databricks-lakehouse
The history of data management platforms.
data management platforms evolved to be data intelligence platforms.
In 1980, businesses needed more than relational databases.

Data warehouse:
pros:
support for Structured & Clean data, eg: csv
Predefined schemas
Business Intelligence (BI)
Analytics

cons:
no support for semi or unstructured data, eg: txt, JSON, image, video
inflexible schemas
struggled with the large volume of data
long processing time

In 2000, big data came into the picture.
Data lakes:
pros:
Flexible data storage (structured or semi or unstructured)
streaming support
cost efficient in the cloud
support for AI and Machine Learning

cons: lacks necessary features from data warehouses
No transactional support
poor data quality and reliability - due to various data formats
slow analysis performance - due to a large volume of data
data governance concerns - due to the unstructured nature of content
data warehouse still needed

In 2021, lakehouse architecture was introduced.
lakehouse - an open and unified foundation for all your data.

![image](https://github.com/user-attachments/assets/7e08071b-438e-4651-8e1d-ddf98feb90da)

![image](https://github.com/user-attachments/assets/90176d92-4639-4054-a73e-9825e9c697af)

key features of a data lakehouse:
1. Transaction support - ACID transactions for concurrent read/write operations
2. schema enforcement and governance - for data integrity
3. data governance - to support privacy regulations
4. BI support - to reduce the latency between obtaining data and drawing insights
5. Decouple storage from compute - each operates in its own cluster, allowing them to scale independently to support their specific needs.
6. open storage formats - Apache Parquet, is open and standardized so that various data tools can access the data directly and efficiently. 
7. support for diverse data types - structured, semi and unstructured data formats can be stored in one location.
8. support for diverse workloads - data science, ML, and analytics
9. end-to-end streaming - for real-time reports, removes the need to have a separate system for data analysis.

Rise of Generative AI.
databricks have brought together two technologies i.e., Data Lakehouse and Generative AI to form Data Intelligence Platform.
![image](https://github.com/user-attachments/assets/70034866-c4e7-4f11-bea8-52e8dfe828bd)

![image](https://github.com/user-attachments/assets/1ca3cac3-c06c-4cba-b694-a6ebf75317f0)

Databricks:
![image](https://github.com/user-attachments/assets/577edafc-9f79-4c9e-a54c-cb4c2a92e9b9)

Databricks data intelligence platform:
![image](https://github.com/user-attachments/assets/9e6a5fdc-47c6-485f-abc5-aec644812457)
Example:
![image](https://github.com/user-attachments/assets/e420fde2-28bc-4f48-afad-c6a6de09fef0)

![image](https://github.com/user-attachments/assets/1b7212db-c659-42af-8bf2-6a5d14827b2a)

![image](https://github.com/user-attachments/assets/2ef0e82e-9584-4e1c-a61c-1c5aecedf5b4)

![image](https://github.com/user-attachments/assets/2e47a6f8-7fb4-456f-a397-0cbac4b8dafe)























