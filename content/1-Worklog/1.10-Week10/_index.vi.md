---
title: "Worklog Tuần 10"
date: 2026-06-22
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

---

### Mục tiêu tuần 10:

- Hoàn thiện luồng xác thực người dùng cốt lõi cho AWS BILLO.
- Xây dựng các chức năng ví cơ bản cho Customer, bao gồm xem số dư, chuyển tiền, nhận tiền bằng QR và lịch sử giao dịch.
- Xây dựng luồng đăng ký kinh doanh và phê duyệt Merchant.
- Triển khai chức năng quản lý cửa hàng và dịch vụ cho Merchant.
- Xây dựng luồng POS và tạo order ban đầu.
- Tích hợp frontend, backend và các dịch vụ AWS cho các chức năng nghiệp vụ chính.
- Làm việc trực tiếp tại văn phòng công ty vào ngày 22/06/2026 từ 08:30 đến 16:30.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                                                                                                                             | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                          |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | --------------------------------------- |
| 2   | - Làm việc trực tiếp tại văn phòng công ty từ 08:30 đến 16:30 <br> - Rà soát hạ tầng AWS đã triển khai ở tuần 9 <br> - Hoàn thiện luồng đăng ký, xác thực OTP, đăng nhập và đăng xuất <br> - Chuẩn hóa định dạng số điện thoại Việt Nam <br> - Kiểm thử xác thực với Amazon Cognito và API Gateway JWT Authorizer                     | 22/06/2026   | 22/06/2026      | Company office                          |
| 3   | - Xây dựng chức năng tự động tạo profile và ví sau khi xác nhận tài khoản <br> - Tạo dữ liệu ví mặc định trên DynamoDB <br> - Xây dựng API hiển thị số dư ví <br> - Kết nối Flutter frontend với API ví <br> - Kiểm tra CloudWatch Logs khi API phát sinh lỗi                                                                         | 23/06/2026   | 23/06/2026      | https://cloudjourney.awsstudygroup.com/ |
| 4   | - Xây dựng chức năng chuyển tiền giữa các Customer <br> - Sử dụng DynamoDB Transaction để cập nhật an toàn ví người gửi và người nhận <br> - Thêm idempotency key để chống giao dịch trùng <br> - Xây dựng QR nhận tiền cá nhân <br> - Xây dựng API lịch sử và chi tiết giao dịch                                                     | 24/06/2026   | 24/06/2026      | https://cloudjourney.awsstudygroup.com/ |
| 5   | - Xây dựng luồng đăng ký kinh doanh cho Merchant <br> - Upload giấy phép kinh doanh lên Amazon S3 bằng pre-signed URL <br> - Xây dựng giao diện Admin xem hồ sơ đăng ký kinh doanh <br> - Triển khai thao tác duyệt hoặc từ chối hồ sơ <br> - Thêm user được duyệt vào Merchant group                                                 | 25/06/2026   | 25/06/2026      | https://cloudjourney.awsstudygroup.com/ |
| 6   | - Tự động tạo thông tin cửa hàng sau khi hồ sơ Merchant được phê duyệt <br> - Xây dựng chức năng quản lý thông tin cửa hàng <br> - Xây dựng chức năng quản lý sản phẩm/dịch vụ: thêm, sửa, xóa và ẩn dịch vụ <br> - Upload ảnh dịch vụ lên Amazon S3 <br> - Xây dựng luồng POS và tạo order ban đầu, hỗ trợ thanh toán tiền mặt và QR | 26/06/2026   | 26/06/2026      | https://cloudjourney.awsstudygroup.com/ |

### Kết quả đạt được tuần 10:

- Hoàn thiện luồng xác thực cốt lõi cho AWS BILLO:
  - Đăng ký tài khoản
  - Xác thực OTP
  - Đăng nhập
  - Đăng xuất
  - Phân quyền API bằng JWT

- Chuẩn hóa xử lý số điện thoại Việt Nam trong quá trình đăng ký và đăng nhập.

- Xây dựng chức năng tự động tạo profile và ví sau khi người dùng xác nhận tài khoản.

- Hiển thị số dư ví của Customer bằng dữ liệu thật từ DynamoDB.

- Xây dựng chức năng chuyển tiền cơ bản giữa các ví Customer.

- Sử dụng DynamoDB Transaction để cập nhật số dư ví an toàn và đảm bảo tính nhất quán dữ liệu.

- Thêm idempotency key để hạn chế việc tạo giao dịch trùng khi người dùng gửi lại request.

- Xây dựng QR nhận tiền cá nhân cho tài khoản Customer.

- Xây dựng API lịch sử giao dịch và chi tiết giao dịch.

- Xây dựng luồng đăng ký kinh doanh cho Merchant và upload giấy phép kinh doanh lên Amazon S3.

- Xây dựng luồng phê duyệt hồ sơ Merchant cho Admin:
  - Xem hồ sơ đang chờ duyệt
  - Duyệt hồ sơ Merchant
  - Từ chối hồ sơ Merchant
  - Thêm user được duyệt vào Merchant group

- Tự động tạo thông tin cửa hàng sau khi hồ sơ Merchant được phê duyệt.

- Xây dựng các chức năng quản lý cửa hàng cơ bản cho Merchant.

- Xây dựng các chức năng quản lý sản phẩm/dịch vụ:
  - Thêm dịch vụ
  - Sửa dịch vụ
  - Xóa dịch vụ
  - Ẩn dịch vụ
  - Upload ảnh dịch vụ lên Amazon S3

- Xây dựng luồng POS và tạo order ban đầu.

- Hỗ trợ các phương thức thanh toán cơ bản cho order:
  - Thanh toán tiền mặt
  - Thanh toán bằng QR

- Tích hợp các chức năng Customer, Merchant và Admin với các dịch vụ AWS gồm Cognito, Lambda, API Gateway, DynamoDB, S3 và CloudWatch.

- Làm việc trực tiếp tại văn phòng công ty vào ngày 22/06/2026 từ 08:30 đến 16:30 và rà soát các lỗi triển khai trong quá trình phát triển.
