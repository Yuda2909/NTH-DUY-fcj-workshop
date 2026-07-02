---
title: "Week 10 Worklog"
date: 2026-06-22
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

---

### Week 10 Objectives:

- Complete the core user authentication flow for AWS BILLO.
- Build basic Customer wallet functions, including wallet balance, money transfer, QR receiving, and transaction history.
- Build the Merchant business registration and approval flow.
- Implement store and service management features for Merchant.
- Build the initial POS and order creation workflow.
- Integrate frontend, backend, and AWS services for main business functions.
- Work directly at the company office on 22/06/2026 from 08:30 to 16:30.

### Tasks to be carried out this week:

| Day | Task                                                                                                                                                                                                                                                                                                                     | Start Date | Completion Date | Reference Material                      |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | --------------------------------------- |
| 2   | - Work directly at the company office from 08:30 to 16:30 <br> - Review the AWS infrastructure from Week 9 <br> - Complete registration, OTP verification, login, and logout flow <br> - Standardize Vietnamese phone number format <br> - Test authentication with Amazon Cognito and API Gateway JWT Authorizer        | 22/06/2026 | 22/06/2026      | Company office                          |
| 3   | - Build Customer profile and wallet initialization after account confirmation <br> - Create default wallet data in DynamoDB <br> - Build wallet balance display API <br> - Connect Flutter frontend to the wallet API <br> - Check CloudWatch Logs when API errors occur                                                 | 23/06/2026 | 23/06/2026      | https://cloudjourney.awsstudygroup.com/ |
| 4   | - Build money transfer between Customer accounts <br> - Use DynamoDB Transaction to update sender and receiver wallets safely <br> - Add idempotency key to prevent duplicate transactions <br> - Build personal QR receiving flow <br> - Build transaction history and transaction detail APIs                          | 24/06/2026 | 24/06/2026      | https://cloudjourney.awsstudygroup.com/ |
| 5   | - Build Merchant business registration flow <br> - Upload business license files to Amazon S3 using pre-signed URL <br> - Build Admin review interface for merchant applications <br> - Implement approve/reject actions for Admin <br> - Add approved users to Merchant group                                           | 25/06/2026 | 25/06/2026      | https://cloudjourney.awsstudygroup.com/ |
| 6   | - Automatically create store profile after merchant approval <br> - Build store management functions <br> - Build product/service management functions: add, edit, delete, and hide services <br> - Upload service images to Amazon S3 <br> - Build initial POS and order creation flow with cash and QR payment support | 26/06/2026 | 26/06/2026      | https://cloudjourney.awsstudygroup.com/ |

### Week 10 Achievements:

- Completed the core authentication flow for AWS BILLO:
  - Registration
  - OTP verification
  - Login
  - Logout
  - JWT-based API authorization

- Standardized Vietnamese phone number handling for user registration and login.

- Built automatic user profile and wallet initialization after account confirmation.

- Displayed wallet balance for Customer accounts using real data from DynamoDB.

- Built the basic money transfer function between Customer wallets.

- Used DynamoDB Transaction to update wallet balances safely and maintain data consistency.

- Added idempotency key handling to prevent duplicate transfer requests.

- Built personal QR receiving flow for Customer accounts.

- Built transaction history and transaction detail APIs.

- Built the Merchant business registration flow and uploaded business license files to Amazon S3.

- Built the Admin approval flow for merchant applications:
  - View pending applications
  - Approve merchant application
  - Reject merchant application
  - Add approved user to Merchant group

- Automatically created a store profile after a merchant application was approved.

- Built basic Merchant store management functions.

- Built product/service management functions:
  - Add service
  - Edit service
  - Delete service
  - Hide service
  - Upload service image to Amazon S3

- Built the initial POS and order creation flow.

- Supported basic payment methods for orders:
  - Cash payment
  - QR payment

- Integrated Customer, Merchant, and Admin functions with AWS services, including Cognito, Lambda, API Gateway, DynamoDB, S3, and CloudWatch.

- Worked directly at the company office on 22/06/2026 from 08:30 to 16:30 and reviewed implementation issues during development.
