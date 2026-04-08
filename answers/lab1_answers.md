# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Đỗ Trung Kiên
**MSSV:** 1871020344

**Lớp/Nhóm:** CNTT18-01

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Cơ sở dữ liệu điểm
- Asset 2: Hệ thống lưu điểm
- Asset 3 (nếu có): Nhật  ký hệ thống

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> Availability
- Sự cố B -> Integrity
- Sự cố C -> Confidentialityr

---

## 3. Phân tích sự cố B
- Threat: Kẻ tấn công truy cập trái phép vào tài khoản của giảng viên để thực hiện thay đổi điểm số.
- Vulnerability: Hệ thống thiếu xác thực đa yếu tố hoặc cơ chế kiểm soát truy cập (Access Control) chưa đủ chặt chẽ để chống truy cập trái phép.
- Mitigation: Triển khai xác thực 2 bước (2FA) cho toàn bộ tài khoản giảng viên và cấu hình lại phân quyền hệ thống.

---

## 4. Reflection
Viết 5-7 dòng.
Nếu là quản trị viên hệ thống, em sẽ ưu tiên xử lý sự cố B (Integrity) trước tiên. Lý do là vì điểm số là dữ liệu cốt lõi của một hệ thống giáo dục; nếu tính toàn vẹn bị phá vỡ, hệ thống sẽ hoàn toàn mất đi sự tin tưởng. Kế tiếp, em sẽ xử lý sự cố C để ngăn việc lộ lọt dữ liệu riêng tư ra ngoài. Cuối cùng mới xử lý sự cố A vì việc gián đoạn đăng nhập chỉ mang tính tạm thời và không làm sai lệch hay rò rỉ dữ liệu quan trọng.


---

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em: FIT4012{A-A-B-I-C-C}

