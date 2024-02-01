# SARS-CoV-2 AWS Data Mining and Insights Project

This project harnesses AWS's powerful cloud infrastructure and Python's analytical capabilities to mine, analyze, and derive insights from COVID-19 data sets. It aims to uncover patterns, trends, and risk factors associated with COVID-19 infection rates across the globe.

## Overview

Leveraging AWS services and Python, this project establishes a robust pipeline for ingesting, transforming, analyzing, and visualizing COVID-19 data. Our goal is to provide meaningful insights into the pandemic's dynamics, supporting public health strategies and research.

## Project Goals

- **Data Ingestion**: Automate the ingestion of diverse COVID-19 data sets into AWS S3.
- **ETL Pipeline**: Utilize AWS Glue for data transformation, preparing it for analysis.
- **Data Lake Formation**: Centralize storage in S3 to facilitate accessible data analysis.
- **Scalability**: Ensure the infrastructure scales efficiently with increasing data volume.
- **Cloud Utilization**: Leverage AWS for high-volume data processing capabilities.
- **Insightful Reporting**: Create dashboards for visualizing trends, patterns, and insights.

## Services Used

- **Amazon S3**: Object storage service for scalable and secure data storage.
- **AWS IAM**: Manages access to AWS services and resources securely.
- **Amazon Redshift**: Data warehousing service for large-scale data analysis.
- **AWS Glue**: Serverless data integration service for ETL processes.
- **Amazon Athena**: Interactive query service to analyze data in Amazon S3 using standard SQL.
- **Jupyter Notebooks**: For data transformation and exploratory data analysis.

## Dataset

The project analyzes publicly available COVID-19 data, focusing on infection rates, recovery cases, and demographic information. Data is ingested from various sources into AWS S3 for processing.

## Architecture Diagram

![Architecture Diagram](./architecture.png)

## Screenshots

### S3 Buckets
![All Buckets](./Screenshots/all_buckets.png)

### AWS Glue Crawlers
![All Crawlers in GLUE for Data](./Screenshots/all_crawlers_in_GLUE_for_data.png)

### ETL Jobs in Glue
![All ETL Jobs in GLUE](./Screenshots/all_ETL_jobs_in_GLUE.png)

### Athena Tables
![All Tables in ATHENA](./Screenshots/all_tables_in_ATHENA.png)

### Glue Database Tables
![All Tables Inside Database in GLUE Crawler](./Screenshots/all_tables_inside_database_in_GLUE_crawler.png)

### VPC Security Groups
![Custom Security Groups in VPC](./Screenshots/custom_security_groups_in_VPC.png)

### Glue Database After Crawling
![Database in GLUE After Crawling](./Screenshots/database_in_GLUE_after_crawling.png)

### Injected Datasets in S3
![Datasets Injected into S3](./Screenshots/datasets_injected_into_s3.png)

### Dimensional Data in S3
![Dimensional Data in Output Inside S3 Bucket](./Screenshots/dimensional_data_in_output_inside_s3_bucket.png)

### Jupyter Notebook Transformations
![Jupyter Notebook Data Transformations Glimpse](./Screenshots/jupyter_notebook_data_transformations_glimpse.png)

### ETL Job Logs
![Logs of ETL Job](./Screenshots/logs_of_ETL_Job.png)

### Main VPC
![Main VPC](./Screenshots/main_vpc.png)

### External Libraries in S3
![Packages Injected into S3 for External Libraries](./Screenshots/packages_injected_into_s3_for_external_libraries.png)

### Python Script in ETL Job
![Python Script in ETL JOB](./Screenshots/python_script_in_ETL_JOB.png)

### Redshift Cluster Configuration
![Redshift Cluster Custom Config](./Screenshots/redshift_cluster_custom_config.png)

### Redshift Cluster in VPC
![Redshift Cluster on VPC](./Screenshots/redshift_cluster_on_vpc.png)

### Redshift Query Editor
![Redshift Query Editor Database Table Schema Data Deployed Output](./Screenshots/redshift_query_editor_database_table_schema_data_deployed_output.png)

![Redshift Query Editor Database Table Schema Data Deployed Output 2](./Screenshots/redshift_query_editor_database_table_schema_data_deployed_output_2.png)

### IAM User Roles
![Roles Assigned to My IAM User](./Screenshots/roles_assigned_to_my_IAM_user.png)

### Redshift Schema in Query Editor
![Schema in Query Editor V2 Redshift Cluster](./Screenshots/schema_in_query_editor_v2_redshift_cluster.png)

### Test Bucket Data
![Test Bucket Data Stored While Transformation](./Screenshots/test_bucket_data_stored_while_transformation.png)
