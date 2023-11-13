# IDS 706 Mini Project 11 -- Data Pipeline with Databricks

## Goal

Create a data pipeline using Databricks

Include at least one data source and one data sink

This repo is following the end-to-end tutorial by Databricks: https://docs.databricks.com/en/getting-started/data-pipeline-get-started.html


## Preparation

1. Azure Databricks
2. Create a self-defined cluster
3. Import Song Dataset
4. Perform data analysis in Databricks

## Run and Result

### Create three Databricks notebooks

![workspace.png](outputs/workspace.png)

### Ingest the raw data
> notebook

![injest.png](outputs/injest.png)

> table created

![data.png](outputs/data.png)

### Prepare the raw data

![prepare.png](outputs/prepare.png)

### Analyse the transformed data

> Which artists released the most songs each year?

![analyse1.png](outputs/analyse1.png)

> Find songs for your DJ list

![analyse2.png](outputs/analyse2.png)

### Create a Databricks job to run the pipeline

![workflow.png](outputs/workflow.png)

![workflow_success.png](outputs/workflow_success.png)


### Workflow
> Schedule the data pipeline job
> set as UTC+5 Evern Monday 08:00

![schedule.png](outputs/schedule.png)

