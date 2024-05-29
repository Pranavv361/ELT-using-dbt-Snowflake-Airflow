## Build ELT pipeline using dbt, Snowflake and Airflow.

## Overview
This project is about the process of building an ELT pipeline using industry-standard tools such as dbt, Snowflake, and Airflow. This repo code also includes basic data modeling techniques, Snowflake RBAC concepts, and how to orchestrate a dbt project using Airflow.

## Tools and Services
- **dbt**: For data transformation and modeling.
- **Snowflake**: For cloud data warehousing.
- **Apache Airflow**: For workflow orchestration.

## What You'll Learn
- Setting up dbt with Snowflake.
- Configuring `dbt_project.yml` and packages.
- Creating source and staging tables.
- Building transformed models including fact tables and data marts.
- Writing macro functions.
- Implementing generic and singular tests.
- Deploying models using Airflow.

[Video Link](https://www.youtube.com/watch?v=OLXkGB7krGo)

## Getting Started
you will need the following:
- A Snowflake account with the necessary permissions to create and manage resources.
- Installed and configured dbt.
- An Apache Airflow instance for orchestration.

### Using the starter project
Try running the following commands:
- dbt run
- dbt test


### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [chat](https://community.getdbt.com/) on Slack for live discussions and support
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices
