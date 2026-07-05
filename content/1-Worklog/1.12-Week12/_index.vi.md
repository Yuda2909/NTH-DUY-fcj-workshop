---
title: "Worklog Tuần 12"
date: 2026-06-29
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---

---

### Mục tiêu tuần 12:

- Tích hợp toàn bộ các chức năng chính của Customer, Merchant và Admin.
- Kiểm thử end-to-end các luồng xác thực, phê duyệt Merchant, quản lý cửa hàng, gọi món tại bàn, bill và thanh toán.
- Sửa các lỗi frontend và backend còn lại.
- Validate và build hạ tầng backend bằng AWS SAM.
- Kiểm tra CloudWatch Logs, tài nguyên AWS và chi phí sử dụng.
- Hoàn thiện tài liệu kỹ thuật, sơ đồ kiến trúc, hướng dẫn sử dụng, dữ liệu demo và nội dung thuyết trình.
- Chuẩn bị dự án cho báo cáo cuối kỳ, đánh giá và bàn giao.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                                                                                                                             | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                          |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | --------------------------------------- |
| 2   | - Tích hợp các chức năng Customer, Merchant và Admin <br> - Kiểm thử đăng ký, xác thực OTP, đăng nhập, đăng xuất và phân quyền theo vai trò <br> - Kiểm thử luồng đăng ký kinh doanh và Admin duyệt Merchant <br> - Rà soát phân quyền API Gateway và Cognito groups                                                                  | 06/07/2026   | 06/07/2026      | https://cloudjourney.awsstudygroup.com/ |
| 3   | - Kiểm thử chức năng quản lý cửa hàng, dịch vụ và bàn <br> - Kiểm thử quét QR bàn, mở menu, tạo order và gọi thêm món vào cùng bill <br> - Kiểm thử cập nhật bill và chống tạo order trùng <br> - Sửa lỗi frontend và backend phát hiện trong quá trình kiểm thử                                                                      | 07/07/2026   | 07/07/2026      | https://cloudjourney.awsstudygroup.com/ |
| 4   | - Kiểm thử luồng thanh toán QR và thanh toán tiền mặt <br> - Kiểm thử hoàn tiền, lịch sử giao dịch và cập nhật trạng thái order <br> - Kiểm thử trường hợp QR thanh toán cũ hết hiệu lực khi bill thay đổi <br> - Kiểm tra CloudWatch Logs sau khi chạy các kịch bản end-to-end                                                       | 08/07/2026   | 08/07/2026      | https://cloudjourney.awsstudygroup.com/ |
| 5   | - Chạy các lệnh kiểm tra và build dự án <br>  + Flutter analyze <br>  + Flutter tests <br>  + Backend tests <br>  + SAM validate <br>  + SAM build <br> - Build phiên bản Flutter Web cuối cùng <br> - Deploy backend cuối cùng lên môi trường AWS development                                                                        | 09/07/2026   | 09/07/2026      | https://cloudjourney.awsstudygroup.com/ |
| 6   | - Kiểm tra tài nguyên AWS và chi phí sử dụng <br> - Dọn dẹp các tài nguyên thử nghiệm không còn sử dụng để tối ưu chi phí <br> - Hoàn thiện sơ đồ kiến trúc hệ thống, tài liệu API và hướng dẫn sử dụng <br> - Chuẩn bị tài khoản demo, dữ liệu demo và kịch bản trình diễn <br> - Đưa mã nguồn lên GitHub và chuẩn bị bàn giao dự án | 10/07/2026   | 10/07/2026      | https://cloudjourney.awsstudygroup.com/ |

### Kết quả đạt được tuần 12:

- Hoàn thành tích hợp các chức năng chính của AWS BILLO cho:
  - Customer
  - Merchant
  - Admin

- Kiểm thử thành công các luồng xác thực và phân quyền:
  - Đăng ký tài khoản
  - Xác thực OTP
  - Đăng nhập
  - Đăng xuất
  - Phân quyền theo vai trò

- Kiểm thử luồng đăng ký kinh doanh của Merchant và quy trình Admin phê duyệt hồ sơ.

- Kiểm thử các chức năng quản lý cửa hàng, quản lý dịch vụ và quản lý bàn.

- Kiểm thử quy trình gọi món tại bàn, bao gồm:
  - Quét QR bàn
  - Mở menu
  - Tạo order
  - Gọi thêm món vào cùng bill
  - Cập nhật bill
  - Chống tạo order trùng

- Kiểm thử các chức năng liên quan đến thanh toán:
  - Thanh toán QR
  - Thanh toán tiền mặt
  - Hoàn tiền
  - Lịch sử giao dịch
  - Cập nhật trạng thái order
  - Vô hiệu hóa QR thanh toán cũ khi bill thay đổi

- Sửa các lỗi frontend và backend còn lại phát sinh trong quá trình kiểm thử tích hợp.

- Chạy các lệnh kiểm tra và build frontend/backend:
  - Flutter analyze
  - Flutter tests
  - Backend tests
  - SAM validate
  - SAM build

- Build phiên bản Flutter Web cuối cùng và deploy backend cuối cùng lên môi trường AWS development.

- Kiểm tra CloudWatch Logs để rà soát lỗi, độ trễ và hành vi hệ thống sau khi chạy kiểm thử end-to-end.

- Rà soát tài nguyên AWS và dọn dẹp các tài nguyên thử nghiệm không sử dụng để giảm chi phí phát sinh.

- Hoàn thiện sơ đồ kiến trúc hệ thống và tài liệu kỹ thuật.

- Hoàn thiện tài liệu API, hướng dẫn cài đặt, hướng dẫn sử dụng và kịch bản demo.

- Chuẩn bị tài khoản demo và dữ liệu mẫu cho buổi báo cáo cuối kỳ.

- Đưa mã nguồn lên GitHub và chuẩn bị bàn giao dự án.

- Hoàn thành phạm vi chính của dự án AWS BILLO và sẵn sàng cho báo cáo, đánh giá cuối kỳ.
