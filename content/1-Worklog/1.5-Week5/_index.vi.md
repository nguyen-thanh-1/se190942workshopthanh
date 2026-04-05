---
title: "Tuần 5: Nghiên cứu AI & Camera"
date: 2025-01-29
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---
<!--
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}
-->

### Mục tiêu tuần 5: (Giai đoạn Ứng dụng)
* Thực hiện việc tích hợp Camera vào trong giao diện web. Giám sát luồng hoạt động chạy mô hình trên tài nguyên của phía người dùng (Client-side) thay vì dồn tải lên server.
* Nghiên cứu tích hợp mô hình YOLO để giám sát camera phòng thi.
* Thiết kế kiến trúc AI Agentic Workflow cho chatbot hỗ trợ học tập.
   * Phác thảo hệ thống ReAct (Reasoning and Acting), khi có câu hỏi hệ thống tự động phân luồng cho 1 trong 4 Agent chuyên môn (Khoa học, Xã hội, Kiến thức chung, Web Search) xử lý.
* Thực hiện thử nghiệm nhận diện vật thể cơ bản (điện thoại, khuôn mặt).

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày kết thúc | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 2 | Tìm hiểu mô hình YOLOv8/v10 cho bài toán phát hiện gian lận. | 02/02 | 02/02 | - |
| 3 | Thiết lập Agentic Workflow cho chatbot bằng Pydantic AI.<br> + Thiết kế Prompts chuyên sâu cho từng tác vụ để đảm bảo Pydantic AI hiểu luật trả lời. | 03/02 | 03/02 | - |
| 4 | Thử nghiệm nhận diện nhiều khuôn mặt trong một khung hình camera. | 04/03 | 04/03 | - |
| 5 | Thiết kế luồng logic: Phát hiện vi phạm -> Chụp ảnh bằng chứng -> Lưu S3. | 05/02 | 05/02 | - |
| 6 | Nghiên cứu cách truyền phát video (streaming) từ Client lên Backend. <br> + Tối ưu hóa prompt cho AI Agent để phân loại câu hỏi của học sinh. <br> + Đánh giá độ trễ của hệ thống AI khi xử lý thời gian thực. | 06/02 | 06/02 | - |

### Kết quả đạt được tuần 5:
* Xác định được mô hình YOLO phù hợp cho việc giám sát thi.
* Kiến trúc Chatbot đa tác vụ (Multi-agent) đã được định hình rõ nét. Mô hình ReAct phân loại thành công chuyên môn câu hỏi thay vì dùng 1 LLM chung chung.
* Hiểu rõ cơ chế capture frame và gửi dữ liệu ảnh từ trình duyệt.
