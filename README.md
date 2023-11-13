# IDS 706 Mini Project 11 -- Data Pipeline with Databricks

## Goal

Create a data pipeline using Databricks

Include at least one data source and one data sink

## Preparation

1. Azure Databricks
2. Create a self-defined cluster
3. Import Song Dataset
4. Perform data analysis in Databricks

## Run and Result

### Create four Databricks notebooks

![workspace.png](outputs/workspace.png)

### Ingest the raw data
> column

![injest.png](outputs/injest.png)

> data

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
> set as UTC+5 Everyday 22:00

![img_1.png](imgs/img_1.png)

## Reference

1.  https://github.com/nogibjj/python-template
2. https://docs.databricks.com/en/getting-started/data-pipeline-get-started.html
