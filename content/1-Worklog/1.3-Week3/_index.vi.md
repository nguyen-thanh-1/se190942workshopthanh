---
title: "Tuần 3: Phân tích & Thiết kế"
date: 2025-01-15
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---
<!--
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}
-->

### Mục tiêu tuần 3: (Giai đoạn Thực hành)
* Phụ trách xây dựng Backend chính, bắt đầu triển khai khung dữ liệu và chuẩn bị cho việc tích hợp AI để hệ thống xử lý mượt mà hơn.
* Phân tích nghiệp vụ chi tiết cho nền tảng EduTrust.
* Thiết kế prompt và luồng xử lý AI.
* Triển khai và thử nghiệm các endpoint API cơ bản.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày kết thúc | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 2 | Họp nhóm thống nhất các module chính: Thi trực tuyến, Giám sát AI và Chatbot. | 19/01 | 19/01 | - |
| 3 | Liệt kê danh sách tính năng (Features List) cho 3 vai trò: Admin, Teacher, Student. | 20/01 | 20/01 | - |
| 4 | - Thử nghiệm các prompt và phát triển prompt cho các AI Agent để tối ưu kết quả đầu ra. <br> - Phân luồng hoạt động cho AI Agent. | 21/01 | 21/01 | - |
| 5 | - Bắt đầu xây dựng FastAPI, xậy dựng endpoint chính về AI và kiểm thử các response để đánh giá prompt có tối ưu không. <br> - Kiểm tra cấu trúc multi-agent có hoạt đọng đúng không | 22/01 | 22/01 | - |
| 6 | Vẽ sơ đồ kiến trúc hệ thống (Platform Architecture) FastAPI <br> + Thiết kế luồng dữ liệu cho tính năng giám sát camera thời gian thực, thực hiện quá trình test và thử nghiệm các mô hình camera AI. <br> + Review lại toàn bộ thiết kế cùng nhóm AI Engineer. | 23/01 | 23/01 | - |

### Kết quả đạt được tuần 3:
* Hoàn thiện khung kiến trúc EduTrust hướng tới khả năng mở rộng trên AWS.
* Xây dựng thành công các endpoint API cơ bản, thử nghiệm và đưa ra được prompt tối ưu cho các Agent khác nhau.
* Xác định rõ công nghệ sử dụng: FastAPI cho Backend, test và thử nghiệm mô hình camera AI.
* Thiết kế thành công cấu trúc cơ bản, dùng làm nền móng cho việc phát triển sau này của dự án.
