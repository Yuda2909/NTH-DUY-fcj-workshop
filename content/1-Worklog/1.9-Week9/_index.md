---
title: "Week 9 Worklog"
date: 2026-06-15
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

---

### Week 9 Objectives:

- Start building the foundation of the AWS BILLO project.
- Set up the initial frontend and backend project structure.
- Create the core AWS serverless infrastructure for the development environment.
- Configure authentication, API access, database, storage, and logging services.
- Deploy the initial backend stack and connect the frontend with real AWS APIs.
- Work directly at the company office on 15/06/2026 from 08:30 to 16:30.

### Tasks to be carried out this week:

| Day | Task                                                                                                                                                                                                                                                                                              | Start Date | Completion Date | Reference Material                      |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | --------------------------------------- |
| 2   | - Work directly at the company office from 08:30 to 16:30 <br> - Review the system design from Week 8 <br> - Initialize the Flutter frontend project structure <br> - Initialize the Node.js backend project structure <br> - Discuss the source code organization and development workflow       | 15/06/2026 | 15/06/2026      | Company office                          |
| 3   | - Create the initial AWS SAM/CloudFormation template <br> - Define the basic serverless resources for the development environment <br> - Prepare the deployment configuration for the Singapore region <br> - Review the relationship between Lambda, API Gateway, DynamoDB, and S3               | 16/06/2026 | 16/06/2026      | https://cloudjourney.awsstudygroup.com/ |
| 4   | - Create and configure Amazon Cognito User Pool <br> - Create user groups for system roles: <br>  + Customer <br>  + Merchant <br>  + Admin <br> - Configure phone number registration and OTP-based authentication <br> - Configure API Gateway JWT Authorizer                                   | 17/06/2026 | 17/06/2026      | https://cloudjourney.awsstudygroup.com/ |
| 5   | - Design and create DynamoDB tables: <br>  + Main Table <br>  + Idempotency Table <br> - Design data models for profile, wallet, merchant, store, product, order, and transaction <br> - Create an S3 bucket for storing images and business license files                                        | 18/06/2026 | 18/06/2026      | https://cloudjourney.awsstudygroup.com/ |
| 6   | - Create initial Lambda functions for core business logic <br> - Build pre-signed URL flow for direct upload to S3 <br> - Configure CloudWatch Logs for Lambda functions <br> - Deploy the development stack to AWS <br> - Connect Flutter frontend with the real AWS API and test basic requests | 19/06/2026 | 19/06/2026      | https://cloudjourney.awsstudygroup.com/ |

### Week 9 Achievements:

- Initialized the AWS BILLO project foundation, including the frontend and backend structure.

- Created the initial Flutter frontend structure for the mobile application.

- Created the initial Node.js backend structure for serverless API development.

- Worked directly at the company office on 15/06/2026 from 08:30 to 16:30 and discussed the project implementation direction.

- Created the initial AWS SAM/CloudFormation template for deploying serverless resources.

- Prepared the development environment in the Singapore region.

- Configured Amazon Cognito User Pool for user authentication.

- Created user groups for role-based access control:
  - Customer
  - Merchant
  - Admin

- Configured the initial authentication flow using phone number and OTP.

- Configured API Gateway JWT Authorizer to protect backend APIs.

- Created DynamoDB tables for application data:
  - Main Table
  - Idempotency Table

- Designed the initial data structure for:
  - User profile
  - Wallet
  - Merchant application
  - Store
  - Product or service
  - Order
  - Transaction

- Created an S3 bucket to store product images, store images, and business license files.

- Built the initial pre-signed URL flow to allow direct file upload to Amazon S3.

- Created initial Lambda functions for core business logic.

- Configured CloudWatch Logs to monitor Lambda execution and troubleshoot errors.

- Successfully deployed the initial backend serverless stack to the development environment.

- Connected the Flutter frontend with real AWS APIs and tested basic authenticated API requests.
