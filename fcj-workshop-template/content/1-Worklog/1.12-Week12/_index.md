---
title: "Week 12 Worklog"
date: 2026-06-29
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---

---

### Week 12 Objectives:

- Integrate all main functions of Customer, Merchant, and Admin.
- Perform end-to-end testing for authentication, merchant approval, store management, table ordering, billing, and payment flows.
- Fix remaining frontend and backend issues.
- Validate and build the backend infrastructure using AWS SAM.
- Review CloudWatch Logs, AWS resources, and cost usage.
- Complete technical documentation, architecture diagram, user guide, demo data, and presentation materials.
- Prepare the project for final report, evaluation, and handover.

### Tasks to be carried out this week:

| Day | Task                                                                                                                                                                                                                                                                                                           | Start Date | Completion Date | Reference Material                      |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | --------------------------------------- |
| 2   | - Integrate Customer, Merchant, and Admin functions <br> - Test registration, OTP verification, login, logout, and role-based authorization <br> - Test merchant registration and admin approval flow <br> - Review API Gateway authorization and Cognito groups                                               | 06/07/2026 | 06/07/2026      | https://cloudjourney.awsstudygroup.com/ |
| 3   | - Test store, service, and table management functions <br> - Test table QR scanning, menu opening, order creation, and adding more items to the same bill <br> - Test bill update and duplicate order prevention <br> - Fix frontend and backend issues found during testing                                   | 07/07/2026 | 07/07/2026      | https://cloudjourney.awsstudygroup.com/ |
| 4   | - Test QR payment and cash payment flows <br> - Test refund handling, transaction history, and order status updates <br> - Test cases where old payment QR becomes invalid after bill changes <br> - Check CloudWatch Logs after running end-to-end scenarios                                                  | 08/07/2026 | 08/07/2026      | https://cloudjourney.awsstudygroup.com/ |
| 5   | - Run project validation and build commands <br>  + Flutter analyze <br>  + Flutter tests <br>  + Backend tests <br>  + SAM validate <br>  + SAM build <br> - Build the final Flutter Web version <br> - Deploy the final backend version to AWS development environment                                       | 09/07/2026 | 09/07/2026      | https://cloudjourney.awsstudygroup.com/ |
| 6   | - Review AWS resources and cost usage <br> - Clean up unused testing resources to optimize cost <br> - Complete system architecture diagram, API documentation, and user guide <br> - Prepare demo accounts, demo data, and presentation script <br> - Push source code to GitHub and prepare project handover | 10/07/2026 | 10/07/2026      | https://cloudjourney.awsstudygroup.com/ |

### Week 12 Achievements:

- Completed integration of the main AWS BILLO functions for:
  - Customer
  - Merchant
  - Admin

- Successfully tested the authentication and authorization flows:
  - Registration
  - OTP verification
  - Login
  - Logout
  - Role-based access control

- Tested the Merchant business registration and Admin approval process.

- Tested store management, service management, and table management functions.

- Tested the table ordering workflow, including:
  - Scanning table QR
  - Opening menu
  - Creating order
  - Adding more items to the same bill
  - Updating bill
  - Preventing duplicate orders

- Tested payment-related functions:
  - QR payment
  - Cash payment
  - Refund handling
  - Transaction history
  - Order status update
  - Payment QR invalidation after bill changes

- Fixed remaining frontend and backend issues found during integration testing.

- Ran frontend and backend validation and testing commands, including:
  - Flutter analyze
  - Flutter tests
  - Backend tests
  - SAM validate
  - SAM build

- Built the final Flutter Web version and deployed the final backend version to the AWS development environment.

- Checked CloudWatch Logs to review errors, latency, and system behavior after end-to-end testing.

- Reviewed AWS resources and cleaned up unused testing resources to reduce unnecessary costs.

- Completed the final system architecture diagram and technical documentation.

- Completed API documentation, installation guide, user guide, and demo script.

- Prepared demo accounts and sample data for the final presentation.

- Pushed the source code to GitHub and prepared the project for final report, evaluation, and handover.

- Completed the main AWS BILLO project scope and prepared the project for final assessment.
