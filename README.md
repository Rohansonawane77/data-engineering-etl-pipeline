# data-engineering-etl-pipeline
End-to-end data engineering project with analysis and ETL pipeline using Python, SQL, and cloud services

Overview

This project focuses on building a secure and scalable data engineering pipeline to ingest, process, and analyze structured and semi-structured YouTube trending video data. The goal is to enable meaningful analysis of video performance across different categories and regions using cloud-native AWS services.

Project Objectives

Data Ingestion
Design a reliable mechanism to ingest data from multiple sources into the system.

ETL Pipeline
Process raw datasets by cleaning, transforming, and converting them into analytics-ready formats.

Centralized Data Lake
Store data from various sources in a centralized and scalable data lake for easy access and management.

Scalability
Ensure the pipeline can handle increasing data volumes without performance degradation.

Cloud-Based Processing
Leverage AWS services to process large datasets efficiently without relying on local infrastructure.

Analytics & Reporting
Build interactive dashboards to answer business questions and uncover trends in YouTube video performance.

AWS Services Used

Amazon S3
Acts as the primary data lake for storing raw and processed datasets with high durability and scalability.

AWS IAM
Manages secure access control and permissions across AWS resources.

AWS Glue
Used for data cataloging, ETL processing, and schema management in a serverless environment.

AWS Lambda
Handles event-driven processing and lightweight transformations without managing servers.

Amazon Athena
Enables ad-hoc querying of data directly from S3 using SQL without data movement.

Amazon QuickSight
Provides interactive dashboards and visualizations to analyze trends and metrics.

Dataset Description

The dataset is sourced from Kaggle and contains daily statistics of trending YouTube videos collected over several months. Each region has its own dataset with up to 200 trending videos per day.

The data includes:

Video title and channel name

Publish time and tags

Views, likes, dislikes, and comment counts

Video descriptions

Region-specific category_id mappings provided through associated JSON files

This dataset enables detailed analysis of video popularity, engagement metrics, and category-wise performance across multiple regions.
