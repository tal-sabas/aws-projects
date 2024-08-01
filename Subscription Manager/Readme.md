# Subscription Manager
This project consisted of the creation of a frontend B2C application allowing end users to view and consolidate all of their subscriptions across their different credit cards (similar to RocketMoney).
This project is deployed on AWS using EKS (Kubernetes) and is composed of a service-oriented architecture. Data integrations include Plaid webhooks and back office file integrations.
There are heavy ETL transformations and logic done in Snowflake.

## Relevant AWS Services Used
- EKS with Fargate
- Cognito
- RDS
- QuickSight
  
## Data Warehousing
This project depends heavily on the use of Snowflake for data warehousing. All transactions and user activity are exported into Snowflake and used for futher analysis. The ETL done in this project uses
Matillion ETL.

## High Level Architecture
![Architecture](https://github.com/tal-sabas/aws-projects/blob/master/Subscription%20Manager/Subscription%20Manager.png)

## App Screenshot
![App](https://github.com/tal-sabas/aws-projects/blob/master/Subscription%20Manager/Subscription%20Manager%20Screenshot.png)
