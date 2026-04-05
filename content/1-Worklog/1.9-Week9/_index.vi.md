---
title: "Tuần 9: Tích hợp RAG & Chatbot AI"
date: 2025-02-26
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---
<!--
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}
-->

### Mục tiêu tuần 9: (Giai đoạn Ứng dụng)
* Hoàn thiện việc phân quyền Role. Phối hợp gắn các chức năng Backend đã làm xong vào Frontend và theo suốt quá trình hoàn thiện giao diện cho Admin và Học sinh.
* Triển khai cơ chế RAG (Retrieval-Augmented Generation) cho hệ thống AI.
   * Là giải pháp thu thập các kiến thức bài giảng thành Vector, đảm bảo Bot không bị "ảo giác" (hallucination) mà bám sát thẳng vào tài liệu trường học.
* Xây dựng giao diện Chatbot thông minh hỗ trợ học tập qua Pydantic AI.
* Tối ưu hóa độ chính xác của AI dựa trên cơ sở tri thức bài giảng.

### Các công việc cần triển khai trong tuần này:
| Thứ | Ngày | Công việc |
| --- | --- | --- |
| 2 | 02/03 | Nghiên cứu quy trình RAG cho trí tuệ nhân tạo dùng Pydantic AI. |
| 3 | 03/03 | Kết nối dữ liệu S3 vào Vector Database phục vụ truy xuất thông tin. |
| 4 | 04/03 | Tích hợp hệ thống Multi-agent để Chatbot có tính chuyên môn cao.<br> + Dồn API kết nối chat lên Next.js qua dạng luồng liên tục để phản hồi gõ chữ. |
| 5 | 05/03 | Xây dựng giao diện Chatbot bằng Next.js, hỗ trợ định dạng Markdown.<br> + Phối hợp ráp nối luồng Backend để chữ trả về theo Stream gõ mượt mà không vỡ UI. |
| 6 | 06/03 | Tối ưu hóa Prompt Engineering để nâng cao chất lượng phản hồi. <br> + Kiểm thử tính năng Chatbot trên cả giao diện Web và Mobile. <br> + Đánh giá hiệu quả Chatbot cùng đội ngũ phát triển AI. |

### Kết quả đạt được tuần 9:
* Chatbot đã có khả năng trả lời các câu hỏi dựa trên nội dung bài giảng.
* Giao diện Chatbot thân thiện, tốc độ phản hồi nhanh nhờ xử lý bất đồng bộ.
* Quy trình RAG hoạt động ổn định, đảm bảo thông tin chính xác cho AI.
