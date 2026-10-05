# Image Create Skill

Bộ skill tạo ảnh phục vụ thương hiệu cá nhân, do **Phạm Văn Trường** phụ trách.

## Skill hiện có

### Tạo bộ ảnh thương hiệu cá nhân 5 bối cảnh

Tạo năm ảnh chân dung riêng biệt từ ảnh khuôn mặt người dùng cung cấp, ưu tiên giữ đặc điểm nhận diện và thay đổi góc mặt, trang phục, tóc, ánh sáng, bối cảnh.

| Ảnh | Bối cảnh | Đặc điểm |
| --- | --- | --- |
| 01 | Đi lại ngoài trời | Bước đi tự nhiên trên phố hoặc lối đi có cây. |
| 02 | Trong ô tô | Góc chính diện, nhìn thẳng camera; chọn ghế lái hoặc ghế phụ. |
| 03 | Phòng thu podcast | Phòng thu chuyên dụng, micro và thiết bị thu phù hợp. |
| 04 | Bàn làm việc có mic | Ngồi sau bàn, micro gắn trên cần đỡ từ bên khung hình. |
| 05 | Đi lại trong nhà | Bước đi tự nhiên trong phòng khách hoặc không gian nhà ở. |

Mặc định: **năm ảnh riêng, khung dọc 4:5**, phong cách ảnh chụp chân thực. Có thể yêu cầu khổ ảnh hoặc phong cách khác. Bộ ảnh có ít nhất ba hướng mặt khác nhau; ảnh trong ô tô giữ góc chính diện.

[Xem nội dung skill](anh-tao-bo-anh-thuong-hieu-ca-nhan/SKILL.md)

## Cách sử dụng

Trong môi trường hỗ trợ skill và có công cụ tạo/chỉnh sửa ảnh:

1. Thêm thư mục `anh-tao-bo-anh-thuong-hieu-ca-nhan` vào vị trí skill mà môi trường của bạn hỗ trợ.
2. Tải ảnh khuôn mặt rõ nét của người cần tạo ảnh.
3. Gọi skill bằng tên và nêu yêu cầu bổ sung nếu có.

Ví dụ:

> Dùng @anh-tao-bo-anh-thuong-hieu-ca-nhan, đây là ảnh khuôn mặt của tôi. Tạo đủ năm cảnh mặc định, phong cách hiện đại, đa góc, giữ đặc điểm nhận diện. Khung dọc 4:5.

Có thể bổ sung màu trang phục, giới tính, phong cách, khổ ảnh hoặc lựa chọn ghế lái/ghế phụ. Nếu ảnh có nhiều người, cần xác định nhân vật chính.

**Lưu ý:** Repository chứa hướng dẫn skill và cấu hình hiển thị, không chứa ứng dụng tạo ảnh độc lập. Việc tải repository không tự cài skill vào ChatGPT. Kết quả phụ thuộc công cụ tạo ảnh; không bảo đảm giống khuôn mặt tuyệt đối.

## Các tệp

| Đường dẫn | Nội dung |
| --- | --- |
| [SKILL.md](anh-tao-bo-anh-thuong-hieu-ca-nhan/SKILL.md) | Hướng dẫn tạo ảnh và kiểm tra kết quả. |
| [agents/openai.yaml](anh-tao-bo-anh-thuong-hieu-ca-nhan/agents/openai.yaml) | Tên hiển thị, mô tả ngắn và câu lệnh gợi ý. |
| [assets/icon.svg](anh-tao-bo-anh-thuong-hieu-ca-nhan/assets/icon.svg) | Biểu tượng của skill. |

Không lưu ảnh khuôn mặt khách hàng trong skill dùng chung.

## Người phụ trách

**Phạm Văn Trường**
