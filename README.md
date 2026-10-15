# CLB Lập Trình PTIT (PTIT Code Club)

> *"Đổi mới sáng tạo — Chinh phục đỉnh cao công nghệ cùng thế hệ trẻ PTIT."*

---

## Danh sách Ban Chấp Hành & Các Ban

| Tên Ban | Trưởng Ban | Liên hệ (Email) |
| :--- | :--- | :--- |
| **Ban Kỹ thuật** | Lê Hồ Thanh Thảo | [thaolht.n26dtcn030@ptit.edu.vn](mailto:thaolht.n26dtcn030@ptit.edu.vn) |
| **Ban Truyền thông** | Nguyễn Văn A | [anv@ptit.edu.vn](mailto:anv@ptit.edu.vn) |
| **Ban Học thuật** | Trần Thị B | [btt@ptit.edu.vn](mailto:btt@ptit.edu.vn) |

---

## Hướng dẫn Gia nhập CLB dành cho Thành viên mới

1. Đăng ký thông tin trực tuyến qua cổng thông tin sinh viên.
2. Clone kho lưu trữ mã nguồn chung của CLB về máy tính cá nhân bằng lệnh Git:
```bash
git clone https://github.com/PTIT-Code-Club/welcome-kit.git
cd welcome-kit
```

---

#### **5. Trả lời 2 bẫy dữ liệu**

* **Trả lời Bẫy 1 (Định dạng email):** Nếu chỉ viết email dạng văn bản thuần túy (Plain Text) như `thaolht.n26dtcn030@ptit.edu.vn`, người xem khi đọc trên giao diện Markdown chỉ thấy một dòng chữ tĩnh bình thường và không thể tương tác. Bằng cách sử dụng cú pháp `[tên hiển thị](mailto:email)`, trình biên dịch sẽ chuyển đổi thành một siêu liên kết có gắn giao thức `mailto:`, giúp khi người dùng bấm vào sẽ tự động kích hoạt ứng dụng gửi email (như Outlook hoặc Gmail) để soạn thư gửi đi ngay lập tức.
* **Trả lời Bẫy 2 (URL không hợp lệ trong hướng dẫn):** Nếu thành viên mới vô tình nhập một URL không hợp lệ (ví dụ thiếu giao thức `https://` hoặc gõ sai định dạng như `github,com`), trình duyệt sẽ nhận diện đó là một **đường dẫn tương đối (Relative URL)** thay vì đường dẫn tuyệt đối ra ngoài Internet. Khi người dùng bấm vào, hệ thống sẽ điều hướng nhầm sang một đường dẫn nội mục dựa trên tên miền hiện tại của trang web (ví dụ: `current-domain.com/github,com`), dẫn đến lỗi **404 Not Found** hoặc làm gián đoạn trải nghiệm điều hướng tài liệu.
