---
title: "Tuần 10: Giám sát & Tối ưu"
date: 2025-03-05
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---
<!--
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}
-->

### Mục tiêu tuần 10: (Giai đoạn Hoàn thành)
* Bắt đầu tiến hành chạy thử nghiệm toàn bộ hệ thống thông qua AWS Amplify, rà soát lại các chức năng Frontend và APIs cuối.
* Thiết lập hệ thống giám sát hiệu suất và log thời gian thực qua CloudWatch.
   * Gắn thêm giám sát cho Log backend (FastAPI), giúp dễ dàng Debug và xem AI Agent mất bao nhiêu thời gian phản hồi ở từng tiến trình.
* Tối ưu bảo mật hạ tầng và quy trình sao lưu dữ liệu tự động.
* Kiểm tra khả năng chịu tải (Stress Test) của hệ thống EduTrust.
   * Giả lập một lượng lớn học sinh làm bài thi và dùng Camera gửi các snapshot liên tục lên S3 cùng lúc để tối ưu rào cản băng thông thực tế.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày kết thúc | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 2 | Cấu hình AWS CloudWatch giám sát log từ FastAPI và Next.js. | 09/03 | 09/03 | - |
| 3 | Debug và tối ưu hóa thời gian phản hồi của các AI Agent. | 10/03 | 10/03 | - |
| 4 | Thiết lập quy trình sao lưu (Backup) tự động cho MongoDB Atlas. | 11/03 | 11/03 | - |
| 5 | Kiểm tra bảo mật S3 Bucket, đảm bảo chỉ truy cập qua Presigned URL. | 12/03 | 12/03 | - |
| 6 | Thực hiện Stress Test giả lập nhiều học sinh cùng thi một lúc.<br> + Kiểm định cường độ tải của AWS EC2 Load Balancer khi gọi API đồng loạt. <br> + Hoàn thiện tài liệu hướng dẫn vận hành và quản trị hệ thống. <br> + Kiểm tra tính ổn định của Docker containers trên môi trường AWS. | 13/03 | 13/03 | - |

### Kết quả đạt được tuần 10:
* Hệ thống được giám sát chặt chẽ, sẵn sàng ứng phó với các sự cố kỹ thuật. Ghi nhận thông suốt Logfire của Pydantic AI về Cloudwatch.
* Quy trình sao lưu dữ liệu tự động đảm bảo an toàn cho bài thi của sinh viên.
* Nắm rõ giới hạn chịu tải của hệ thống để có phương án mở rộng (Scaling).
