# 💘 Dating App Website

## 📝 Mô tả

Website hẹn hò trực tuyến, giúp người dùng tạo hồ sơ cá nhân, tìm kiếm và được gợi ý những đối tượng phù hợp dựa trên sở thích, tiêu chí cá nhân và thuật toán matching. Sau khi hai bên "match" với nhau, người dùng có thể nhắn tin, trò chuyện và kết nối trực tiếp trên nền tảng.

## 🛠 Công nghệ dự kiến

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Firebase (Authentication, Firestore/Realtime Database, Storage, Cloud Functions)
- **Database:** MySQL hoặc SQL Server (lưu trữ dữ liệu có cấu trúc: hồ sơ, lịch sử tương tác, báo cáo vi phạm...)

## ✨ Chức năng dự kiến

### Tài khoản & Hồ sơ
- Đăng ký/đăng nhập bằng Google, xác thực OTP qua email/SĐT
- Xác thực bằng JWT, quản lý/đổi mật khẩu, đăng xuất
- Thiết lập hồ sơ cá nhân: thông tin cơ bản (họ tên, giới tính, ngày sinh, chiều cao, cân nặng, tôn giáo, quê quán...), học vấn & nghề nghiệp, tính cách & lối sống
- Thiết lập tiêu chí tìm kiếm đối tượng mong muốn

### Tìm kiếm & Kết nối
- Tìm kiếm hồ sơ theo nhiều tiêu chí (bộ lọc)
- Thuật toán matching gợi ý đối tượng có độ tương thích cao
- Like / Dislike / Super Like, danh sách người đã thích, được thích, đã match

### Nhắn tin
- Trò chuyện thời gian thực sau khi match
- Gửi emoji, sticker, hình ảnh, hỗ trợ video call
- Hiển thị trạng thái online/offline, hoạt động gần nhất

### An toàn & Kiểm duyệt
- Báo cáo, chặn tài khoản vi phạm (giả mạo, quấy rối, spam...)
- Kiểm duyệt tự động nội dung người dùng đăng tải (ảnh, hồ sơ, tin nhắn)
- Phát hiện spam / tài khoản ảo

### Bảo mật & Hiệu năng (mục tiêu)
- Mã hoá mật khẩu (bcrypt), HTTPS toàn hệ thống, chống SQL Injection/XSS, rate limiting
- Thời gian phản hồi API ≤ 2s, tải danh sách hồ sơ ≤ 1s, độ trễ chat real-time ≤ 500ms
- Hỗ trợ tối thiểu 10,000 người dùng đồng thời
