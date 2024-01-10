# Real-Estate-Data-Integration-on-AWS-with-Apache-Airflow-
## Overview
This GitHub repository contains a comprehensive guide and codebase for building an end-to-end Python ETL (Extract, Transform, Load) process. The project focuses on extracting real estate properties data from the Zillow Rapid API, automating the data flow through AWS services, and visualizing the results using Amazon QuickSight.

## Project Workflow
Data Extraction from Zillow Rapid API:
Utilizes Python to extract real estate properties data from Zillow Rapid API.

## Amazon S3 Data Storage:
Loads the extracted data into an Amazon S3 bucket for efficient storage.

## Lambda Functions Automation:
Triggers a series of Lambda functions to automate subsequent data processing tasks.

## Data Transformation with Apache Airflow:
Employs Apache Airflow to transform the data, converting it into CSV format.
Utilizes the S3KeySensor operator to monitor data upload completion to an S3 bucket.

## Amazon Redshift Data Loading:
Loads the transformed data into Amazon Redshift for further analysis.

## Data Visualization with Amazon QuickSight:
Connects Amazon QuickSight to the Amazon Redshift cluster to visualize Zillow data.

## Tools Used
- Apache Airflow:
Open-source platform for orchestrating and scheduling workflows.
- Amazon Web Services (AWS):
Cloud platform hosting the entire ETL process.
