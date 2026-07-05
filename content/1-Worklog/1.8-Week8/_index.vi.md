---
title: "Worklog Tuần 8"
date: 2026-06-08
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

---

### Mục tiêu tuần 8:

- Phân tích đề tài AWS BILLO: ví điện tử kết hợp POS và quản lý cửa tiệm.
- Xác định các vai trò chính trong hệ thống gồm Customer, Merchant và Admin.
- Xác định phạm vi MVP và các yêu cầu chức năng cốt lõi.
- Phân tích user flow, business flow và yêu cầu dữ liệu của hệ thống.
- Nghiên cứu các dịch vụ AWS phù hợp với kiến trúc serverless tối ưu chi phí.
- Thiết kế kiến trúc hệ thống ban đầu, wireframe và luồng nghiệp vụ cho dự án.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                                                                                                                        | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                          |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | --------------------------------------- |
| 2   | - Phân tích đề tài AWS BILLO <br> - Xác định mục tiêu chính của hệ thống: ví điện tử, xem trước biên lai điện tử, POS cho cửa tiệm và quản lý cửa hàng <br> - Xác định ba vai trò chính: <br>  + Customer <br>  + Merchant <br>  + Admin                                                                                         | 08/06/2026   | 08/06/2026      |                                         |
| 3   | - Xác định phạm vi MVP và yêu cầu chức năng <br> - Phân tích các chức năng chính của Customer: <br>  + Đăng ký và đăng nhập <br>  + Xem số dư ví <br>  + Chuyển tiền <br>  + Thanh toán QR <br>  + Lịch sử giao dịch và hóa đơn <br> - Phân tích yêu cầu của Merchant và Admin                                                   | 09/06/2026   | 09/06/2026      | https://cloudjourney.awsstudygroup.com/ |
| 4   | - Phân tích luồng xác thực và phân quyền: <br>  + Đăng ký bằng số điện thoại <br>  + Xác thực OTP <br>  + Đăng nhập và đăng xuất <br>  + Phân quyền theo vai trò <br> - Phân tích quy trình đăng ký và phê duyệt kinh doanh <br> - Phác thảo user flow và business flow                                                          | 10/06/2026   | 10/06/2026      | https://cloudjourney.awsstudygroup.com/ |
| 5   | - Phân tích luồng quản lý cửa hàng của Merchant: <br>  + Quản lý thông tin cửa hàng <br>  + Quản lý sản phẩm/dịch vụ <br>  + Quản lý bàn <br>  + Tạo order <br>  + Thanh toán bằng QR <br> - Nghiên cứu cấu trúc dữ liệu cho biên lai điện tử và chi tiết đơn hàng                                                               | 11/06/2026   | 11/06/2026      | https://cloudjourney.awsstudygroup.com/ |
| 6   | - Nghiên cứu các dịch vụ AWS phù hợp với hệ thống: <br>  + Amazon Cognito <br>  + AWS Lambda <br>  + Amazon API Gateway <br>  + Amazon DynamoDB <br>  + Amazon S3 <br>  + Amazon CloudWatch <br> - So sánh kiến trúc serverless với kiến trúc sử dụng EC2/VPC <br> - Phác thảo kiến trúc AWS tổng thể và tổng hợp hướng thiết kế | 12/06/2026   | 12/06/2026      | https://cloudjourney.awsstudygroup.com/ |

### Kết quả đạt được tuần 8:

- Hoàn thành phân tích ban đầu về đề tài AWS BILLO và làm rõ định hướng của hệ thống.

- Xác định được ba vai trò chính trong hệ thống:
  - Customer
  - Merchant
  - Admin

- Xác định phạm vi MVP và các chức năng cần ưu tiên trong phiên bản đầu tiên của dự án.

- Phân tích các chức năng chính của Customer:
  - Đăng ký và đăng nhập tài khoản
  - Xem số dư ví
  - Chuyển tiền
  - Thanh toán QR
  - Xem lịch sử giao dịch
  - Xem trước biên lai điện tử

- Phân tích các chức năng chính của Merchant:
  - Đăng ký kinh doanh
  - Quản lý thông tin cửa hàng
  - Quản lý sản phẩm hoặc dịch vụ
  - Quản lý bàn
  - Tạo order
  - Hỗ trợ thanh toán bằng QR

- Phân tích các chức năng chính của Admin:
  - Kiểm tra hồ sơ đăng ký kinh doanh
  - Duyệt hoặc từ chối hồ sơ Merchant
  - Quản lý vai trò người dùng và quyền truy cập của Merchant

- Hoàn thành user flow và business flow ban đầu cho các luồng đăng ký, xác thực, phê duyệt kinh doanh, quản lý cửa hàng, tạo order và thanh toán QR.

- Nghiên cứu các dịch vụ AWS phù hợp với hệ thống, bao gồm:
  - Amazon Cognito cho xác thực và quản lý nhóm người dùng
  - AWS Lambda cho xử lý logic nghiệp vụ
  - Amazon API Gateway cho quản lý API
  - Amazon DynamoDB cho lưu trữ dữ liệu NoSQL
  - Amazon S3 cho lưu trữ hình ảnh và tài liệu
  - Amazon CloudWatch cho ghi log và giám sát

- So sánh kiến trúc serverless với kiến trúc sử dụng EC2/VPC và lựa chọn hướng serverless tối giản để tối ưu chi phí cho MVP.

- Hoàn thành thiết kế kiến trúc AWS ban đầu, ghi chú wireframe, user flow và business flow để chuẩn bị cho giai đoạn triển khai ở các tuần tiếp theo.
