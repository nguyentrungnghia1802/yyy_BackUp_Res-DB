# yyy_BackUp_Res-DB

## Mục đích

Thư mục này dùng để lưu trữ các bản sao lưu (backup) cơ sở dữ liệu và các tài nguyên (resources) liên quan đến dự án Hanaya Shop.

## Cấu trúc thư mục

- `hanaya-shop/database/`: Chứa file backup cơ sở dữ liệu (ví dụ: `hanaya-shop-backup.sql`).
- `hanaya-shop/img/`: Lưu trữ hình ảnh sản phẩm, ảnh về shop, ảnh về các loại hoa, quà lưu niệm, video demo, v.v.
	- Các thư mục con như `About/`, `Hoa đặc biệt/`, `Hoa sáp/`, `Hoa tươi/`, `Home/`, `Post/`, `Quà lưu niệm/` giúp phân loại hình ảnh theo chủ đề.
	- `Video Demo/`: Chứa video demo về shop.
- `Profile_img/`: Lưu trữ các hình ảnh profile, logo, hình đại diện liên quan đến shop.

## Hướng dẫn sử dụng

- Sử dụng các file backup trong `database/` để phục hồi dữ liệu khi cần thiết.
- Các hình ảnh và video trong `img/` và `Profile_img/` có thể dùng cho website, tài liệu quảng bá, hoặc các mục đích truyền thông khác.
- Thư mục này chỉ dùng để lưu trữ, không chứa mã nguồn hoặc các file thực thi.

## Lưu ý

- Đảm bảo cập nhật file backup cơ sở dữ liệu thường xuyên để tránh mất mát dữ liệu.
- Khi thêm mới tài nguyên, hãy phân loại vào đúng thư mục để dễ quản lý.
- Không chia sẻ công khai các file backup nếu chứa thông tin nhạy cảm.
