---
title: "Tuần 1: Thiết lập & Đề tài"
date: 2025-01-01
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---
<!--
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}
-->

### Mục tiêu tuần 1: (Giai đoạn Tìm hiểu)
* [Team Leader] Đảm nhận vai trò Leader, họp bàn lên ý tưởng chi tiết về dự án EduTrust, thống nhất ý kiến của mọi người về các hướng phát triển chức năng cốt lõi.
* Thành lập nhóm đồ án và thống nhất lựa chọn đề tài EduTrust.
* Thiết lập môi trường làm việc nhóm qua Git, Jira.
   * Theo mô hình Git Monorepo để dễ quản lý, đồng bộ hóa cả Backend (FastAPI) và Frontend (Next.js/React).
   * Áp dụng Agile trên Jira, tạo các Epic và Ticket nhỏ gọn cho 5 thành viên để tránh bị xung đột task.
* Nghiên cứu sơ bộ các dịch vụ Cloud cần thiết (IAM, S3, Amplify).
   * Thử nghiệm phân quyền nghiêm ngặt với IAM (Access Key hạn chế quyền) để Backend sau này thao tác an toàn với Bucket S3.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày kết thúc | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 2 | Làm quen và kết nối với các thành viên trong nhóm 5 người.<br> + Xác lập và phân rã các Role rõ ràng cho mảng Backend và AI để chuẩn bị cho kiến trúc chung. | 05/01 | 05/01 | - |
| 3 | Thảo luận và thống nhất tên đề tài: "EduTrust - Nền tảng giám sát thi trực tuyến". | 06/01 | 06/01 | - |
| 4 | Thiết lập cấu trúc Git monorepo và quy trình làm việc nhóm. | 07/01 | 07/01 | - |
| 5 | Làm quen với Jira, phân chia vai trò cho các thành viên. | 08/01 | 08/01 | - |
| 6 | Đăng ký tài khoản AWS, cấu hình bảo mật MFA cho tài khoản Root. <br> + Tìm hiểu khái quát về các mô hình IaaS, PaaS cho phát triển Fullstack. <br> + Tổng kết tuần và chuẩn bị nghiên cứu database. | 09/01 | 09/01 | - |

### Kết quả đạt được tuần 1:
* Thống nhất đề tài và có kế hoạch sơ bộ cho đồ án.
* Môi trường làm việc (Git/Jira) đã sẵn sàng. Sẵn sàng quy trình cấp phát Ticket cho từng người chống trùng lặp tính năng.
* Hoàn thành thiết lập bảo mật cho tài khoản AWS cá nhân.
