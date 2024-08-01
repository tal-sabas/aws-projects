# Government Data Project
 This project's purpose is to gather a variety of public data sources available by the US government, and store the data in a way that can be used for deeper insights and analysis.
 This project provides a mechanism to combine multiple public data sources, easier querying of the data, and gives flexibility to build AI or reporting on top of the sources.
 This is a 100% AWS-based product, with the exception of Tableau.

 ## Interface
 The data displayed by this pipeline is delivered by a custom application built using ReactJs, and hosted on AWS Amplify. This application is backed by AWS Cognito for user authenciation and management,
 and uses the API Gateway + lambda design pattern to fetch data from a REST API.

## Relevant AWS Services Used
- AWS Glue
- Lambda
- Athena/S3
- Tableau
- QuickSight
- Kinesis
- Amplify
- Cognito

### Data Ingestion Pipeline
![diagram](https://github.com/tal-sabas/aws-projects/blob/master/Government%20Data%20Pipeline/Government%20Data%20Project.png)

### Portal
![portal](https://github.com/tal-sabas/aws-projects/blob/master/Government%20Data%20Pipeline/Government%20Data%20Pipeline-B2C%20Portal.png)
