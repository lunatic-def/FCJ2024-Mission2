---
title : "Introduction"
date :  "`r Sys.Date()`" 
weight : 1 
chapter : false
pre : " <b> 1. </b> "
---
**- This workshop is my attemp to learn about Lambda severless framework and Iac, this will include creating serverless E-commerce Microservice simple infrastruture.**
**Using Infrastructor as code (CDK-typescript) and JS code for lambda function**

**2 main part:**
- Develop infrastruture with AWS CDK typescript
- Develop lambda function with AWS SDK and NodeJS

![topology](/images/1.intro/topology.JPG)

***STEPS**
1) Create DynamoDB tables for Product service -> Basket service -> Order service
2) Create Lambda function for Product service -> Basket service -> Order service
3) Implement Lambda function for Product service -> Basket service -> Order service
4) Create API Gateway
5) EventBridge: eventrules, eventbus
6) Create SQS queue