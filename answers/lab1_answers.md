# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Ngô Văn Hiếu

**MSSV:** 1871020234

**Lớp/Nhóm:** CNTT 18-02

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Bảng điểm sinh viên
- Asset 2: Tài khoản sinh viên
- Asset 3 (nếu có):

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> Không đăng nhập được (Availability)
- Sự cố B -> Điểm bị sửa (Integrity)
- Sự cố C -> Lộ dữ liệu (Confidentiality)

---

## 3. Phân tích sự cố B
- Threat: Hacker truy cập trái phép
- Vulnerability: Mật khẩu yếu
- Mitigation: Yêu cầu phê duyệt khi sửa điểm

---

## 4. Reflection
Viết 5-7 dòng.

Nếu là quản trị viên hệ thống, em sẽ ưu tiên xử lý vấn đề liên quan đến Integrity trước, vì việc điểm bị sửa sai ảnh hưởng trực tiếp đến quyền lợi sinh viên và uy tín hệ thống. Em sẽ triển khai xác thực đa yếu tố và phân quyền rõ ràng để hạn chế truy cập trái phép. Đồng thời, em sẽ bổ sung hệ thống log và cơ chế phê duyệt khi thay đổi điểm để tăng khả năng kiểm soát và truy vết. Sau đó mới xử lý các vấn đề khác như cải thiện hiệu năng và tính sẵn sàng của hệ thống.

---
  
## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em:
FIT4012{A-A-B-I-C-C}
