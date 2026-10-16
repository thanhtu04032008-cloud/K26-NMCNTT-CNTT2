# **Phần 1. Phân tích bài toán:**
## Giải thích tại sao Markdown lại giúp AI xử lý nhanh hơn dựa trên cơ chế chia nhỏ Token:
- Vì Markdown lược bỏ hoàn toàn các thẻ cú pháp thừa thãi, cùng một nội dung thông tin được truyền đi sẽ tạo ra ít token hơn đáng kể
- Số lượng token đầu vào và đầu ra ít hơn giúp giảm thời gian tính toán ma trận của mô hình AI, từ đó giúp chatbot phản hồi nhanh hơn
- Sử dụng Markdown giúp doanh nghiệp tiết kiệm chi phí gọi API đáng kể cho hệ thống khi phải xử lý hàng nghìn lượt hỏi đáp mỗi ngày
- Các token trong văn bản Markdown tập trung hoàn toàn vào nội dung ngữ nghĩa thực tế. Điều này giúp AI hiểu đúng ý định của người nông dân và đưa ra câu trả lời chính xác, tránh việc mô hình bị phân tâm bởi các đoạn mã đánh dấu cấu trúc rườm rà
# **Phần 2. So sánh & Đánh giá:**
## Bảng so sánh Markdown và HTML
| Tiêu chí so sánh | Markdown | HTML |
| :---: | :---: | :---: |
| Cú pháp định dạng | Sử dụng các ký tự trực quan, tối giản | Sử dụng các cặp thẻ đóng/mở dài
| Mật độ Token | Thấp: Lược bỏ các thẻ rườm rà, giúp văn bản gọn gàng và tạo ra ít token hơn khi AI xử lý | Cao: Chứa lượng lớn các ký tự thẻ kỹ thuật, làm tăng số lượng token đầu vào/đầu ra |
| Tốc độ xử lý của AI | Nhanh: Giảm tải ma trận tính toán của mô hình, giúp chatbot phản hồi nhanh hơn | Chậm hơn: AI phải xử lý nhiều token thừa mang tính cấu trúc giao diện |
| Chi phí vận hành API | Tiết kiệm: Giảm thiểu đáng kể số lượng token tiêu thụ trên mỗi yêu cầu | Tốn kém: Chi phí tăng cao do lượng token phình to bởi các thẻ HTML lặp lại |
| Độ dễ đọc cho con người | Rất cao: Ngay cả khi chưa render, người nông dân hoặc kỹ thuật viên vẫn dễ dàng đọc hiểu nội dung thô | Thấp: Khó đọc và khó kiểm tra trực tiếp bằng mắt thường do bị che lấp bởi mã thẻ |
| Mục đích sử dụng chính | Viết tài liệu kỹ thuật, ghi chú, README dự án, giao tiếp nhanh với AI | Xây dựng cấu trúc trang web, thiết kế giao diện đồ họa phức tạp trên trình duyệt |
## Giải pháp tối ưu cho hệ thống GreenTech
- Giúp giảm bớt áp lực tài chính khi vận hành hệ thống với hàng nghìn lượt truy vấn mỗi ngày từ người nông dân
- Tốc độ sinh token nhanh giúp nâng cao trải nghiệm người dùng, đảm bảo đưa ra lời khuyên kịp thời về canh tác, tưới tiêu
- Dễ dàng kiểm tra, chỉnh sửa hoặc bổ sung tài liệu hướng dẫn kỹ thuật mà không sợ bị rối mắt bởi các đoạn mã đánh dấu cấu trúc rườm rà
