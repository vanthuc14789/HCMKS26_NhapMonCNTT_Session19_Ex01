# BÀI 1: XỬ LÝ CẢNH BÁO ĐĂNG NHẬP

## 1. Chỉ ra ký tự lạ trong URL và giải thích

URL đáng ngờ: `https://githúb.com/login`

- Ký tự lạ là chữ **ú** thay vì chữ **u** trong URL thật: `https://github.com`.
- Đây là kỹ thuật **Homograph Attack**, sử dụng ký tự Unicode có hình dạng gần giống ký tự thật để tạo website giả mạo.
- Kẻ tấn công lợi dụng sự nhầm lẫn để đánh lừa người dùng và đánh cắp tài khoản, mật khẩu.

## 2. Quy trình kiểm tra URL trước khi nhập Master Password

**Bước 1: Kiểm tra bằng mắt thường**
- Đọc kỹ từng ký tự trong tên miền.
- Kiểm tra lỗi chính tả, ký tự lạ và dấu tiếng Việt.
- Không nhấn vào liên kết từ email hoặc tin nhắn đáng ngờ.

**Bước 2: Sử dụng công cụ**
- Truy cập trực tiếp website chính thức: https://github.com.

**Bước 3: Bảo vệ tài khoản**
- Không nhập mật khẩu khi chưa xác minh tên miền.
- Bật xác thực hai yếu tố (2FA).
- Không cung cấp mã OTP hoặc mã xác thực cho người khác.
