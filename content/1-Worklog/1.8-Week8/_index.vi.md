---
title: "Tuần 8: Quản lý dữ liệu & Báo cáo"
date: 2025-02-19
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---
<!--
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}
-->

### Mục tiêu tuần 8: (Giai đoạn Ứng dụng)
* Triển khai logic luồng theo sát việc chia role trên UI (Nhà trường - Admin, Giáo viên, Học sinh) với các nhóm chức năng phù hợp và bảo mật chặt chẽ.
* Xây dựng module quản lý và báo cáo kết quả thi của sinh viên.
   * Chú trọng phát triển chức năng xuất và trích xuất dữ liệu bài thi (Excel/CSV) kết hợp lịch sử gian lận để Admin/Teacher lập báo cáo chi tiết nhất.
* Tích hợp dịch vụ gửi thông báo tự động (Amazon SES).
* Tối ưu hóa hiệu năng truy xuất dữ liệu từ MongoDB.

### Các công việc cần triển khai trong tuần này:
| Thứ | Ngày | Công việc |
| --- | --- | --- |
| 2 | 23/02 | Phát triển tính năng xem danh sách sinh viên dự thi cho giáo viên.<br> + Kết nối dữ liệu báo cáo gian lận S3 vào màn hình trực quan. |
| 3 | 24/02 | Lập trình logic xuất báo cáo kết quả thi ra định dạng Excel/CSV. |
| 4 | 25/02 | Tích hợp Amazon SES để gửi email kết quả tự động cho sinh viên. |
| 5 | 26/02 | Thiết lập Redis để cache kết quả tìm kiếm và danh sách lớp học. |
| 6 | 27/02 | Sửa lỗi định dạng tiếng Việt khi xuất báo cáo từ MongoDB. <br> + Kiểm tra luồng gửi email thực tế với tài khoản Amazon SES. <br> + Review mã nguồn module báo cáo cùng nhóm Backend. |

### Kết quả đạt được tuần 8:
* Hệ thống có khả năng quản lý và xuất dữ liệu báo cáo chuyên nghiệp. Hoàn thành luồng xuất báo cáo đầy đủ, FrontEnd nhận và hiển thị hình ảnh minh chứng vi phạm trực quan.
* Tự động hóa quy trình thông báo kết quả thi qua Email.
* Tốc độ truy xuất dữ liệu tăng đáng kể nhờ tích hợp Redis Caching.
