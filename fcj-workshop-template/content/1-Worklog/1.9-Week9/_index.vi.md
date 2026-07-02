---
title: "Worklog Tuần 9"
date: 2026-06-15
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

---

### Mục tiêu tuần 9:

- Bắt đầu xây dựng nền tảng cho dự án AWS BILLO.
- Khởi tạo cấu trúc frontend và backend ban đầu.
- Tạo hạ tầng serverless cốt lõi trên AWS cho môi trường phát triển.
- Cấu hình các dịch vụ xác thực, API, cơ sở dữ liệu, lưu trữ và ghi log.
- Triển khai backend ban đầu và kết nối frontend với API thật trên AWS.
- Làm việc trực tiếp tại văn phòng công ty vào ngày 15/06/2026 từ 08:30 đến 16:30.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                                                                                 | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                          |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | --------------------------------------- |
| 2   | - Làm việc trực tiếp tại văn phòng công ty từ 08:30 đến 16:30 <br> - Xem lại thiết kế hệ thống ở tuần 8 <br> - Khởi tạo cấu trúc dự án Flutter frontend <br> - Khởi tạo cấu trúc dự án Node.js backend <br> - Trao đổi về cách tổ chức mã nguồn và quy trình phát triển                   | 15/06/2026   | 15/06/2026      | Company office                          |
| 3   | - Tạo AWS SAM/CloudFormation template ban đầu <br> - Định nghĩa các tài nguyên serverless cơ bản cho môi trường dev <br> - Chuẩn bị cấu hình triển khai tại region Singapore <br> - Ôn lại mối liên hệ giữa Lambda, API Gateway, DynamoDB và S3                                           | 16/06/2026   | 16/06/2026      | https://cloudjourney.awsstudygroup.com/ |
| 4   | - Tạo và cấu hình Amazon Cognito User Pool <br> - Tạo các group cho các vai trò trong hệ thống: <br>  + Customer <br>  + Merchant <br>  + Admin <br> - Cấu hình đăng ký bằng số điện thoại và xác thực OTP <br> - Cấu hình API Gateway JWT Authorizer                                     | 17/06/2026   | 17/06/2026      | https://cloudjourney.awsstudygroup.com/ |
| 5   | - Thiết kế và tạo các bảng DynamoDB: <br>  + Main Table <br>  + Idempotency Table <br> - Thiết kế mô hình dữ liệu cho profile, wallet, merchant, store, product, order và transaction <br> - Tạo S3 bucket để lưu hình ảnh và giấy phép kinh doanh                                        | 18/06/2026   | 18/06/2026      | https://cloudjourney.awsstudygroup.com/ |
| 6   | - Tạo các Lambda function ban đầu cho logic nghiệp vụ cốt lõi <br> - Xây dựng luồng pre-signed URL để upload trực tiếp lên S3 <br> - Cấu hình CloudWatch Logs cho Lambda function <br> - Deploy stack dev lên AWS <br> - Kết nối Flutter frontend với API thật và kiểm thử request cơ bản | 19/06/2026   | 19/06/2026      | https://cloudjourney.awsstudygroup.com/ |

### Kết quả đạt được tuần 9:

- Đã khởi tạo nền tảng ban đầu cho dự án AWS BILLO, bao gồm cấu trúc frontend và backend.

- Tạo cấu trúc Flutter frontend ban đầu cho ứng dụng mobile.

- Tạo cấu trúc Node.js backend ban đầu để phát triển API theo hướng serverless.

- Làm việc trực tiếp tại văn phòng công ty vào ngày 15/06/2026 từ 08:30 đến 16:30 và trao đổi về hướng triển khai dự án.

- Tạo AWS SAM/CloudFormation template ban đầu để triển khai các tài nguyên serverless.

- Chuẩn bị môi trường phát triển tại region Singapore.

- Cấu hình Amazon Cognito User Pool để xác thực người dùng.

- Tạo các group phục vụ phân quyền theo vai trò:
  - Customer
  - Merchant
  - Admin

- Cấu hình luồng xác thực ban đầu bằng số điện thoại và OTP.

- Cấu hình API Gateway JWT Authorizer để bảo vệ các API backend.

- Tạo các bảng DynamoDB phục vụ lưu trữ dữ liệu ứng dụng:
  - Main Table
  - Idempotency Table

- Thiết kế cấu trúc dữ liệu ban đầu cho:
  - User profile
  - Wallet
  - Merchant application
  - Store
  - Product hoặc service
  - Order
  - Transaction

- Tạo S3 bucket để lưu hình ảnh sản phẩm, hình ảnh cửa hàng và giấy phép kinh doanh.

- Xây dựng luồng pre-signed URL ban đầu để cho phép upload file trực tiếp lên Amazon S3.

- Tạo các Lambda function ban đầu cho logic nghiệp vụ cốt lõi.

- Cấu hình CloudWatch Logs để theo dõi quá trình chạy Lambda và hỗ trợ xử lý lỗi.

- Deploy thành công backend serverless ban đầu lên môi trường dev.

- Kết nối Flutter frontend với API thật trên AWS và kiểm thử các request cơ bản có xác thực.
