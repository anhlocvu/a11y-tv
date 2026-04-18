# a11y tv v1.0

Phần mềm xem truyền hình siêu trợ năng cho người khiếm thị.

## Yêu cầu hệ thống
1. **Python 3.10+** (Đã có sẵn trong môi trường này).
2. **VLC Media Player**: Bạn cần cài đặt bản VLC 64-bit trên Windows để trình phát video hoạt động.
   - Tải tại: [https://www.videolan.org/vlc/](https://www.videolan.org/vlc/)

## Cách khởi chạy
Sử dụng `uv` để chạy ứng dụng:
```bash
uv run main.py
```

## Các phím tắt chính
### Tại màn hình chính:
- **Tab**: Di chuyển giữa ô Tìm kiếm và Danh sách kênh.
- **Enter** (khi ở danh sách kênh): Phát kênh đã chọn.
- **Chuột phải** (hoặc phím Application): Mở menu tùy chọn.

### Tại màn hình trình phát (Toàn màn hình):
- **Mũi tên Lên**: Tăng âm lượng.
- **Mũi tên Xuống**: Giảm âm lượng.
- **M**: Tắt/Bật tiếng.
- **Dấu cách (Space)**: Tạm dừng/Tiếp tục.
- **Escape (Esc)**: Đóng trình phát và quay lại danh sách.

## Tính năng
- Tự động lấy danh sách kênh từ nguồn IPTV thế giới uy tín.
- Ưu tiên hiển thị các kênh Việt Nam lên đầu.
- Tìm kiếm nhanh chóng theo tên hoặc quốc gia.
- Giao diện tương thích cực tốt với NVDA.
