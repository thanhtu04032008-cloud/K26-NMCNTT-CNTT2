# Khái niệm Hàng đợi (Queue) trong Cấu trúc dữ liệu

## 1. Hàng đợi (Queue) là gì?
Hiểu một cách đơn giản nhất, **Hàng đợi (Queue)** hoạt động giống hệt như **hàng người xếp hàng chờ mua vé xem phim** hoặc chờ thanh toán ở quầy siêu thị. 

Người nào đến trước sẽ được phục vụ trước, và người đến sau buộc phải đứng phía sau chờ đến lượt mình. Trong khoa học máy tính, nguyên tắc này được gọi tắt là **FIFO** (viết tắt của cụm từ tiếng Anh *First In, First Out* - **Vào trước, ra trước**).

## 2. Các thao tác cơ bản trong Queue
Để quản lý một hàng đợi, người ta thường sử dụng hai thao tác chính sau đây:

* **Enqueue (Thao tác thêm vào):** Hành động một phần tử mới bước vào cuối hàng đợi. Giống như có thêm một khách hàng mới xếp vào cuối hàng người chờ.
* **Dequeue (Thao tác lấy ra):** Hành động phần tử ở đầu hàng đợi được phục vụ xong và rời đi. Giống như người đứng đầu tiên ở quầy được mua vé và bước ra khỏi hàng.

## 3. Ứng dụng thực tế
Mô hình **Queue** xuất hiện rất nhiều trong cuộc sống hàng ngày và hệ thống máy tính:
* Khi bạn gửi nhiều tài liệu ra **máy in**, các lệnh in sẽ được xếp thành hàng đợi để in lần lượt từng tờ theo thứ tự ai gửi trước.
* Khi chơi game trực tuyến, hệ thống **Matchmaking** sẽ xếp những người chơi bấm tìm trận vào một hàng đợi chung để ghép cặp theo thứ tự thời gian.
