# AWS: COVID-19 Full Stack Data Project for Analysis

## Description
This project focuses on building a data engineering solution for processing and analyzing COVID-19 data using AWS services. Performing data modeling, data wrangling and extract-load-transform using python on the COVID-19 Data Lake available on registry of open data AWS using various AWS tools such as boto3, Glue, S3, Athena and Redshift.

## Requirements
- AWS Account
- Python
- PowerBI

## Technology Stack
- AWS Glue - data transformation
- AWS Amazon S3 - Storing the data
- Crawler - Used to extract all the schema and information straight from S3
- Amazon Athena - Running adhoc sql queries on the available data in S3
- Amazon Redshift - storing the tranfromed dimensional model in datawarehouse
- Python


## Data Source
The primary data source is COVID-19 data, which may include datasets from official health organizations or public repositories.

- Data Set: https://registry.opendata.aws/aws-covid19-lake/

## Architecture

![](/images/arc.png)

## Data Modeling
The data is modeled based on the COVID-19 dataset structure, with considerations for efficient querying and analysis.

![](/images/dim.png)

## Deploy the Solution
1. Clone the repository.
2. Navigate to the project directory.
3. Use Terraform to deploy the necessary infrastructure on AWS.

## Step-by-Step Guide
1. Running Crawlers on the data uploaded in S3
2. nalysing data using AWS Athena query editor
3. Building the ER-Data Model
4. ETL jobs in python
5. Saving result in S3
6. Building the Dimensional Model
7. Building Dimensional schema in Redshift
8. Storing the dimensional model into Redshift

## Dashboard

![](/images/dashboard.png)

## Contributing
Feel free to contribute to the project by opening issues or submitting pull requests. Follow standard GitHub contribution guidelines.

**Note**: Ensure to configure AWS credentials and update the necessary configuration files before deploying the solution.
