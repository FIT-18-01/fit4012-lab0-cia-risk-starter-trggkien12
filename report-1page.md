# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- Cơ sở dữ liệu điểm
- Nhật ký hệ thống

**CIA mapping:**
- Sự cố A -> Availability
- Sự cố B -> Integrity
- Sự cố C -> Confidentiality

**Phân tích sự cố B:**
- Threat: Kẻ tấn công truy cập trái phép vào tài khoản giảng viên.
- Vulnerability: Mật khẩu yếu, thiếu xác thực đa yếu tố.
- Mitigation: Triển khai xác thực 2 bước (2FA) cho giảng viên.

### 4. Kết luận ngắn
Qua bài lab, em học được cách áp dụng mô hình CIA vào một hệ thống thực tế và cách phân tích rủi ro cơ bản. Phần khó nhất là phân biệt rõ ràng giữa threat và vulnerability. Điều cần chú ý nhất là phải xác định đúng tài sản cốt lõi bị ảnh hưởng để đưa ra biện pháp bảo vệ phù hợp.