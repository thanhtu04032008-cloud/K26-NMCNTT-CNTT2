# **Phần 1. Phân tích:**
## Xác định Input/Output và sơ đồ phối hợp phần cứng của hệ thống trang trại
**Input:**
- Đo lường hàm lượng nước có trong đất tại các luống hoa lan
- Thu thập dữ liệu môi trường vi khí hậu trong nhà kính
- Cho phép người nông dân kích hoạt tưới khẩn cấp bằng tay khi cần thiết
- Ngưỡng độ ẩm tối thiểu được thiết lập qua giao diện phần mềm

**Output:**
- Kích hoạt hệ thống tưới phun sương hoặc tưới gốc khi độ ẩm xuống dưới ngưỡng cho phép
- Cập nhật trực quan các thông số thời gian thực tại hiện trường
- Phát tín hiệu khi hệ thống gặp sự cố
- Gửi dữ liệu nhật ký lên hệ thống giám sát để người quản lý theo dõi qua internet
# **Phần 2. Kiểm thử:**
## Giả định RAM bị đầy dữ liệu nhật ký
***Lưu ý:*** Khi hệ thống hoạt động liên tục trong thời gian dài, tập tin nhật ký  hoặc bộ nhớ đệm (RAM Buffer) có thể bị đầy do ghi log quá nhiều, dẫn đến treo thiết bị hoặc gián đoạn chu trình điều khiển
**Cách xử lý:**
- Ngừng ghi các sự kiện không quan trọng bằng cách chuyển mức cấu hình log sang chế độ `WARNING` hoặc `ERROR`
- Trích xuất file nhật ký hiện tại sang thẻ nhớ ngoài hoặc đẩy lên Cloud để phục vụ công tác kiểm tra, gỡ lỗi
- Thực hiện lệnh xóa cache hoặc khởi động lại vi điều khiển theo đúng quy trình tuần tự để giải phóng dung lượng RAM mà không làm mất cấu hình hệ thống
- Thiết lập cơ chế tự động xoay vòng file log để tự động xóa bớt các file nhật ký cũ vượt quá 7 ngày nhằm phòng ngừa tái diễn sự cố
