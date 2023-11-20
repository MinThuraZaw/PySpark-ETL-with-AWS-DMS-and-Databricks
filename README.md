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
1) Setup the source database for DMS (for example, permission for the user or enable logs for DMS to read)
2) Create source and target endpoints in DMS (RDBMS for source and S3 bucket for target)
3) Setup database migration task in DMS with ongoing replication.
4) Load data from S3 bucket into delta talbe with autoloader in Databricks. 
