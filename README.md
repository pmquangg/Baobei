# Quiet Confession — website tỏ tình

Website tĩnh, responsive, ưu tiên điện thoại. Không cần backend.

## Xem thử trên máy
Mở `index.html` bằng trình duyệt. Để kiểm tra đầy đủ ảnh/video/nhạc, hãy đặt media theo đúng tên file bên dưới.

## Thay nội dung cá nhân
Mở `index.html` và chỉnh:
- Tiêu đề ở phần hero.
- Các đoạn văn ở phần “The beginning” và “What I feel”.
- Chữ ký `Someone who cares`.
- Ngày ở chân trang.

## Thêm ảnh, video và nhạc
Chép file của bạn vào thư mục `assets/`:
- `photo-1.jpg`
- `photo-2.jpg`
- `photo-3.jpg`
- `our-video.mp4`
- `music.mp3`

Ảnh nên dùng JPG/WebP, video MP4 (H.264), nhạc MP3. Nên nén media để website tải nhanh trên điện thoại.

## Đưa website lên mạng và tạo QR
1. Tải thư mục này lên GitHub.
2. Import repository vào Vercel (hoặc Netlify), framework preset chọn **Other**, build command để trống, output directory là `.`.
3. Sau khi deploy, lấy URL HTTPS do nền tảng cấp.
4. Tạo QR Code trỏ tới URL đó và in lên thiệp.

Lưu ý: Video và nhạc YouTube cần người xem chủ động nhấn Play; trình duyệt thường chặn tự phát âm thanh. Cần kết nối internet để phát nội dung.
