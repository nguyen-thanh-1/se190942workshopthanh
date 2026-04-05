---
title: "Tuần 7: Hạ tầng & Tự động hóa"
date: 2025-02-12
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---
<!--
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}
-->

### Mục tiêu tuần 7: (Giai đoạn Ứng dụng)
* [Frontend Support & Roles] Bắt đầu tiến hành hỗ trợ cho team Frontend xây dựng UI, thiết kế logic nâng cấp và chia các Role rõ ràng cho hệ thống.
* Thiết lập hạ tầng mạng VPC/EC2 cho hệ thống EduTrust.
* Triển khai hạ tầng dưới dạng mã (Infrastructure as Code - IaC).
* Cấu hình cân bằng tải (Load Balancer) và bảo mật SSL/HTTPS.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày kết thúc | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 2 | Khởi tạo VPC, Subnet và EC2 cho Backend EduTrust. | 16/02 | 16/02 | - |
| 3 | Triển khai hạ tầng lên AWS bằng các kịch bản tự động (IaC). | 17/02 | 17/02 | - |
| 4 | Cấu hình Application Load Balancer để điều phối lưu lượng. | 18/02 | 18/02 | - |
| 5 | Tích hợp SSL (HTTPS) cho domain qua AWS Certificate Manager. | 19/02 | 19/02 | - |
| 6 | Thực hiện Load Testing kiểm tra khả năng chịu tải của hạ tầng. <br> + Hoàn thiện tài liệu mô tả hạ tầng mạng (Security Groups). <br> + Đánh giá hiệu năng và bảo mật mạng cơ bản. | 20/02 | 20/02 | - |

### Kết quả đạt được tuần 7:
* Hạ tầng mạng AWS được thiết lập bài bản theo mô hình chuẩn của đồ án.
* Hệ thống đạt chuẩn bảo mật HTTPS, sẵn sàng cho người dùng truy cập.
* Tự động hóa triển khai giúp quản lý tài nguyên linh hoạt hơn.
