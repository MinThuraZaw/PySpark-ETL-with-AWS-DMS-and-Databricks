### About
Implement change data capture on operational source system, store and process all the changes log data for further analytics.

<br>

### Pipeline
![alt text](https://github.com/MinThuraZaw/PySpark-ETL-with-AWS-DMS-and-Databricks/blob/main/images/dms_pipeline.jpg)

<br>

### Requirements
1) Operational Database (any database or storage compatible with DMS)
2) AWS DMS (a running replication instance)
3) AWS S3
4) Databricks (all-purpose cluster, better with unity catalog enabled)

**Languages**
* PySpark
* Spark SQL

<br>

### Development Steps
1) Create source and target endpoints in DMS (RDBMS for source and S3 bucket for target)
2) Setup database migration task in DMS with ongoing replication.
3) 
