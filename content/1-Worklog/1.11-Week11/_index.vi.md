---
title: "Worklog Tuần 11"
date: 2026-06-29
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

---

### Mục tiêu tuần 11:

- Xây dựng quy trình gọi món tại bàn cho Merchant và Customer.
- Sinh QR riêng cho từng bàn và cho phép Customer mở menu bằng cách quét QR bàn.
- Xây dựng luồng bill trực tiếp, bao gồm thêm món, cập nhật bill và tạo QR thanh toán.
- Cải thiện trạng thái order, xử lý hoàn tiền và kiểm tra hiệu lực của payment session.
- Cải thiện UI/UX cho các màn hình Authentication, Customer, Merchant và Admin.
- Sửa các lỗi frontend và backend quan trọng phát sinh trong quá trình kiểm thử tích hợp.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                                                                                                                                 | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                          |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | --------------------------------------- |
| 2   | - Xây dựng chức năng quản lý bàn cho Merchant <br>  + Thêm bàn <br>  + Sửa bàn <br>  + Khóa bàn <br>  + Xóa bàn <br> - Sinh QR riêng cho từng bàn <br> - Cho phép Merchant tải QR bàn để in và dán lên bàn                                                                                                                                | 29/06/2026   | 29/06/2026      | https://cloudjourney.awsstudygroup.com/ |
| 3   | - Xây dựng luồng Customer quét QR bàn <br> - Cho phép Customer mở menu sau khi quét QR bàn <br> - Hiển thị bàn đang sử dụng trên Customer Home <br> - Cho phép Customer mở lại bàn đang dùng mà không cần quét QR lần nữa <br> - Kiểm thử camera quét QR và đọc QR từ ảnh                                                                 | 30/06/2026   | 30/06/2026      | https://cloudjourney.awsstudygroup.com/ |
| 4   | - Xây dựng luồng tạo order từ menu của bàn <br> - Cho phép Customer chọn món và gửi order cho Merchant <br> - Hỗ trợ gọi thêm món vào cùng một bill <br> - Chống tạo order trùng khi Customer gửi lại request nhiều lần <br> - Lưu dữ liệu order và bill vào DynamoDB                                                                     | 01/07/2026   | 01/07/2026      | https://cloudjourney.awsstudygroup.com/ |
| 5   | - Xây dựng chức năng Merchant quản lý bill trực tiếp <br> - Cho phép Merchant mở bàn để xem bill hiện tại <br> - Cho phép Merchant thêm hoặc xóa món khách gọi bằng miệng <br> - Lưu thay đổi bill mà không tạo order trùng <br> - Tạo lại QR thanh toán khi bill thay đổi                                                                | 02/07/2026   | 02/07/2026      | https://cloudjourney.awsstudygroup.com/ |
| 6   | - Xây dựng luồng QR thanh toán từ bill <br> - Tạo bill QR chứa thông tin món, số lượng, tổng tiền và mã đơn <br> - Vô hiệu hóa QR thanh toán cũ khi bill thay đổi <br> - Cập nhật trạng thái order sau thanh toán <br> - Cải thiện xử lý hoàn tiền và hiển thị trạng thái order <br> - Cải thiện UI/UX và sửa lỗi overflow, lỗi xử lý ảnh | 03/07/2026   | 03/07/2026      | https://cloudjourney.awsstudygroup.com/ |

### Kết quả đạt được tuần 11:

- Hoàn thành các chức năng quản lý bàn cơ bản cho Merchant:
  - Thêm bàn
  - Sửa bàn
  - Khóa bàn
  - Xóa bàn
  - Sinh QR cho từng bàn
  - Tải QR bàn để in

- Xây dựng luồng Customer quét QR bàn.

- Cho phép Customer mở menu cửa hàng bằng cách quét QR của bàn.

- Hiển thị bàn đang sử dụng trên Customer Home và cho phép Customer mở lại bàn mà không cần quét QR lần nữa.

- Xây dựng luồng tạo order từ menu của bàn.

- Hỗ trợ gọi thêm món vào cùng một bill mà không tạo bill trùng.

- Xây dựng chức năng Merchant quản lý bill trực tiếp, bao gồm:
  - Xem bill hiện tại theo bàn
  - Thêm món khách gọi trực tiếp
  - Xóa món khỏi bill
  - Lưu thay đổi bill
  - Tránh tạo order trùng

- Tạo QR thanh toán từ thông tin bill, bao gồm:
  - Món đã gọi
  - Số lượng
  - Tổng tiền
  - Mã đơn

- Vô hiệu hóa QR thanh toán cũ khi nội dung bill thay đổi.

- Cập nhật trạng thái order sau khi thanh toán và cải thiện xử lý hoàn tiền.

- Cải thiện chức năng quét QR bằng camera và đọc QR từ hình ảnh.

- Cải thiện UI/UX cho các màn hình Authentication, Customer, Merchant và Admin.

- Tạo các thành phần giao diện dùng chung như theme, màu sắc, card, button và widget.

- Sửa các lỗi giao diện quan trọng như overflow layout và lỗi xử lý hình ảnh.

- Hoàn thành quy trình gọi món tại bàn từ quét QR, tạo order, cập nhật bill đến thanh toán.
