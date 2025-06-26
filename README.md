 Café Clickstream Data Analytics on AWS
This project demonstrates the creation of a data pipeline to collect, process, visualize, and analyze web traffic (clickstream) data from a café website hosted on AWS. It involves using services like Amazon EC2, CloudWatch, Cloud9, S3, and Athena to gain insights into user behavior and site performance.

 Project Overview
The café website generates clickstream data such as page views and order submissions. This data is collected using Apache web server logs and streamed to AWS CloudWatch for real-time monitoring and analysis. The processed logs are also stored in S3 for long-term backup and further insights using dashboards and queries.

 Architecture
User interacts with the website hosted on an EC2 Instance.

Apache Web Server logs traffic and interactions.

Logs are collected using the CloudWatch Agent.

Logs are analyzed using CloudWatch Logs Insights.

Data is visualized in CloudWatch Dashboards.

Logs are backed up to Amazon S3.

Further analysis is done using Athena (optional).

Final Backup
Uploaded access logs to S3 bucket for archival

 Key AWS Services Used
Amazon EC2

Amazon Cloud9

Amazon CloudWatch (Logs + Insights + Dashboards)

Amazon S3

Amazon IAM

 Learnings
Real-time log analysis and visualization

Configuring Apache for JSON-based logging

Setting up AWS CloudWatch dashboards

Using AWS CLI to manage log flow and backups

Performing structured analysis using Logs Insights



