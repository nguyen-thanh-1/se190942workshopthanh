---
title: "Tuần 4: Phát triển Backend & Auth"
date: 2025-01-22
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---
<!--
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}
-->

### Mục tiêu tuần 4: (Giai đoạn Thực hành)
* [Backend & AI] Tập trung làm Backend và đặc biệt nhấn mạnh vào việc cải thiện, tinh chỉnh thêm Prompt cho Pydantic AI agent để tối ưu hệ thống ReAct, bảo đảm chuyên gia AI trả lời chính xác.
* Xây dựng nền tảng Backend bằng FastAPI.
   * Đảm nhận lập trình Backend, thiết lập các API Route cơ bản hỗ trợ hệ thống Router tập trung cho thi cử và kết nối AI thay vì các Framework cồng kềnh khác, giúp tối ưu phương thức Streaming tốc độ.
* Triển khai hệ thống xác thực người dùng (Authentication) qua JWT/Cognito.
* Kết nối và thực hiện các thao tác CRUD cơ bản trên MongoDB Atlas.

### Các công việc cần triển khai trong tuần này:
| Thứ | Ngày | Công việc |
| --- | --- | --- |
| 2 | 26/01 | Khởi tạo dự án FastAPI, cấu hình cấu trúc thư mục Monorepo.<br> + Thiết lập cấu trúc thư mục tiêu chuẩn, dựng sẵn API Router mở đầu cho luồng chức năng thi cử. |
| 3 | 27/01 | Kết nối MongoDB Atlas bằng Motor (async driver) và kiểm tra kết nối. |
| 4 | 28/01 | Xây dựng logic Register/Login, tích hợp JWT cho phân quyền RBAC.<br> + Cấu hình Middleware quản lý JWT token để chặn đứng truy cập trái phép vào tài nguyên Camera/Đề thi. |
| 5 | 29/01 | Viết API CRUD cho quản lý thông tin lớp học và đề thi. |
| 6 | 30/01 | Kiểm thử bảo mật API bằng Swagger UI và ReDoc. <br> + Tối ưu hóa xử lý lỗi (Exception Handlers) trong FastAPI. <br> + Tổng kết tháng đầu tiên và lập kế hoạch nghiên cứu AI. |

### Kết quả đạt được tuần 4:
* Hệ thống Backend cơ bản đã hoạt động ổn định với FastAPI.
* Xác thực người dùng và phân quyền Admin/Teacher/Student đã hoàn tất. Backend đã chặt chẽ trong việc định tuyến API đúng người đúng việc.
* Dữ liệu đã được lưu trữ và truy xuất thành công từ MongoDB Cloud.
