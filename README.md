# cfn-ctrail-cli

> An automatically deployed event monitoring and analyses solution for the AWS Cloud.

**cfn-ctrail-cli** is a shell script that provisions and configures various AWS Resources through an assortment of API calls and an AWS Cloudformation template. It creates an integrated framework that facilitates the collection, transformation and presentation of a time-series of processed cloud activity logs, in the form of observable Event Records as well as a straightforward mechanism with which to better analyse and interpret what is taking place, in a detailed way, within an AWS Account.

[![Linux](https://img.shields.io/badge/OS-Linux-blue?logo=linux)](https://github.com/cloudemprise/cfn-ovpn-cli)
![Bash](https://img.shields.io/badge/Bash->=v4.0-green?logo=GNU%20bash)
[![awscli](https://img.shields.io/badge/awscli->=v2.0-green.svg)](https://github.com/aws/aws-cli)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

## Introduction

It is important to be able to know what is happening in your cloud environment. One should be able to infer what is actually occurring within it by gathering information about the status of resources and the events they produce. These events represent how resources are changing and how they are interacting with external elements and also among themselves. Detecting those events and presenting them in the manner that is easy to analyse and understand is what this project is about.

Resources for implementing a comprehensive logging and alerting strategy in an AWS environment. Included are customizable configuration items and packages, as well as guides to configure logging and alerting for AWS account activity, threat detection, configuration compliance, and service-specific logs. In addition to enabling logging and monitoring, resources for reviewing, analysing and visualizing logs are also covered.

### Notes

- Cloudtrail event monitoring 
- integrated with AWS Glue Database(ETL)
- Amazon Athena is an interactive query service
- makes it easy to analyse data directly in Amazon Simple Storage Service (Amazon S3) using standard SQL. 
- Athena Tables and SQL search templates.
- Cloudwatch logs and alarms.
- queries to identify trends
- CloudTrail logs to analyse operational activity for security and compliance.
- standard SQL to run ad-hoc queries
- insights
- SIEM https://en.wikipedia.org/wiki/Security_information_and_event_management
- facilitate the human analysis.
- Some mention of Insight fucntionality.
- Athena : slice and dice data.


### AWS Services Overview

Lits of Integrated Services

#### AWS Glue Documentation

AWS Glue is a serverless data-preparation service for extract, transform, and load (ETL) operations. It makes it easy for data engineers, data analysts, data scientists, and ETL developers to extract, clean, enrich, normalize, and load data. AWS Glue reduces the time it takes to start analyzing your data from months to minutes. It provides you with both visual and code-based interfaces to make data preparation easy. Data engineers and ETL developers can use AWS Glue Studio to create, run, and monitor ETL jobs with a few clicks. Data analysts and data scientists can use AWS Glue DataBrew to visually clean up and normalize data without writing code. 


#### Amazon Athena Documentation

Amazon Athena is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL. Athena is serverless, so there is no infrastructure to setup or manage, and you pay only for the queries you run. To get started, simply point to your data in S3, define the schema, and start querying using standard SQL. 


#### AWS CloudTrail Documentation

With AWS CloudTrail, you can monitor your AWS deployments in the cloud by getting a history of AWS API calls for your account, including API calls made via the AWS Management Console, the AWS SDKs, the command line tools, and higher-level AWS services. You can also identify which users and accounts called AWS APIs for services that support CloudTrail, the source IP address the calls were made from, and when the calls occurred. You can integrate CloudTrail into applications using the API, automate trail creation for your organization, check the status of your trails, and control how administrators turn CloudTrail logging on and off. 


#### Amazon CloudWatch Documentation

Amazon CloudWatch provides a reliable, scalable, and flexible monitoring solution that you can start using within minutes. You no longer need to set up, manage, and scale your own monitoring systems and infrastructure. 


### Reference Material

https://asecure.cloud/g/strategy_logging/
