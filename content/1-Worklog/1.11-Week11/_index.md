---
title: "Week 11 Worklog"
date: 2026-06-29
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

---

### Week 11 Objectives:

- Build the table ordering workflow for Merchant and Customer.
- Generate unique QR codes for each table and allow Customer to open the menu by scanning table QR.
- Build the live bill workflow, including adding items, updating bills, and generating payment QR.
- Improve order status, refund handling, and payment session validation.
- Enhance UI/UX for Authentication, Customer, Merchant, and Admin screens.
- Fix major frontend and backend issues found during integration testing.

### Tasks to be carried out this week:

| Day | Task                                                                                                                                                                                                                                                                                                                                           | Start Date | Completion Date | Reference Material                      |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | --------------------------------------- |
| 2   | - Build table management functions for Merchant <br>  + Add table <br>  + Edit table <br>  + Lock table <br>  + Delete table <br> - Generate a unique QR code for each table <br> - Allow Merchant to download table QR for printing                                                                                                           | 29/06/2026 | 29/06/2026      | https://cloudjourney.awsstudygroup.com/ |
| 3   | - Build Customer table QR scanning flow <br> - Allow Customer to open the menu after scanning table QR <br> - Display the current active table on Customer Home <br> - Allow Customer to reopen the active table without scanning QR again <br> - Test camera QR scanning and QR reading from image                                            | 30/06/2026 | 30/06/2026      | https://cloudjourney.awsstudygroup.com/ |
| 4   | - Build order creation from table menu <br> - Allow Customer to select items and send order to Merchant <br> - Support adding more items to the same bill <br> - Prevent duplicate order creation when Customer submits the same request multiple times <br> - Store order and bill data in DynamoDB                                           | 01/07/2026 | 01/07/2026      | https://cloudjourney.awsstudygroup.com/ |
| 5   | - Build Merchant live bill management <br> - Allow Merchant to open a table and view the current bill <br> - Allow Merchant to add or remove items ordered verbally by Customer <br> - Save bill updates without creating duplicate orders <br> - Regenerate payment QR when bill content changes                                              | 02/07/2026 | 02/07/2026      | https://cloudjourney.awsstudygroup.com/ |
| 6   | - Build bill payment QR flow <br> - Generate bill QR containing order information, item quantity, total amount, and order code <br> - Disable old payment QR when bill changes <br> - Update order status after payment <br> - Improve refund handling and order status display <br> - Improve UI/UX and fix overflow or image handling errors | 03/07/2026 | 03/07/2026      | https://cloudjourney.awsstudygroup.com/ |

### Week 11 Achievements:

- Completed basic table management functions for Merchant:
  - Add table
  - Edit table
  - Lock table
  - Delete table
  - Generate table QR
  - Download table QR for printing

- Built the Customer table QR scanning workflow.

- Allowed Customer to open the store menu by scanning a table QR code.

- Displayed the active table on Customer Home and allowed Customer to reopen the table without scanning QR again.

- Built the order creation flow from the table menu.

- Supported adding more items to the same bill without creating duplicate bills.

- Built Merchant live bill management, including:
  - View current bill by table
  - Add items ordered verbally
  - Remove items from bill
  - Save bill changes
  - Avoid duplicate order creation

- Generated payment QR from bill information, including:
  - Ordered items
  - Quantity
  - Total amount
  - Order code

- Disabled old payment QR when the bill content was updated.

- Updated order status after payment and improved refund handling.

- Improved QR scanning by supporting both camera scan and QR reading from image.

- Improved UI/UX for Authentication, Customer, Merchant, and Admin screens.

- Created reusable UI components such as theme, colors, cards, buttons, and common widgets.

- Fixed major frontend issues such as layout overflow and image handling errors.

- Completed the main table ordering workflow from QR scanning to order creation, bill update, and payment.
