# MARVEL-AWS-PIPELINE

## Overview
An end-to-end AWS pipeline designed to collect and analyze Marvel movie box office performance data. This pipeline leverages various AWS services such as **AWS Lambda**, **S3 Storage**, and **EventBridge** triggers to automate data collection, processing, and storage.

## Features
- **Data Collection:** Pulls data from multiple sources, including **Wikipedia** and the **OMDB API**, to gather information on Marvel movies.
- **AWS Lambda:** Used to process data and handle tasks such as API requests and data transformation.
- **S3 Storage:** Stores raw and processed data for easy access and future analysis.
- **EventBridge Trigger:** Automates the pipeline by triggering Lambda functions based on predefined events.

## Workflow
1. Data is pulled from multiple sources (Wikipedia, OMDB API).
2. AWS Lambda functions process and transform the data.
3. Processed data is stored in **S3 Storage** for further analysis.
4. **EventBridge** is used to schedule and trigger pipeline execution.

## Use Case
The pipeline is designed to analyze Marvel movies' **box office performance**, providing insights and facilitating further analysis on movie success.

