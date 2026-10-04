# [Thực hành] Tạo trang web cá nhân với CSS

Dự án bài thực hành tổng hợp xây dựng trang web cá nhân với các kiến thức nền tảng trong HTML5 & CSS3.

## 📌 Mục đích bài thực hành
- Nhúng tệp CSS độc lập vào tài liệu HTML qua thẻ `<link>`.
- Sử dụng các bộ chọn CSS cơ bản: bộ chọn phần tử (`body`, `header`, `ul`, `table`, `footer`), bộ chọn lớp (`.avatar`, `.profile`, `.hobbies`, `.goals`).
- Định dạng đường viền (`border`, `border-radius: 50%` bo tròn ảnh đại diện).
- Điều chỉnh màu nền (`background-color`, `background-image`) và màu chữ (`color`).
- Định kiểu cho danh sách không có thứ tự với `list-style-type: square;`.
- Định kiểu bảng thông tin liên hệ gọn gàng với `border-collapse: collapse;`.

---

## 🛠 Cấu trúc mã nguồn
- `index.html`: Cấu trúc tài liệu HTML5 gồm 6 phần:
  1. **Tiêu đề chính**: Khối `header` chào mừng.
  2. **Ảnh đại diện & Giới thiệu bản thân**: Khối `.profile` với ảnh đại diện bo tròn.
  3. **Danh sách sở thích**: Khối `.hobbies` sử dụng danh sách `<ul>` dấu vuông.
  4. **Mục tiêu học tập**: Khối `.goals` chia sẻ định hướng lập trình.
  5. **Bảng thông tin liên hệ**: Khối `footer` chứa bảng `<table>` liên hệ (Email, Facebook).
- `style.css`: File định dạng giao diện trang web theo toàn bộ yêu cầu của bài học.
- `avatar.jpg`: Ảnh đại diện lập trình viên sắc nét.
- `README.md`: Tài liệu dự án.

---

## 📋 Tóm tắt các thuộc tính CSS được áp dụng
| Thuộc tính CSS | Phần tử | Ý nghĩa |
| :--- | :--- | :--- |
| `background-color: #4CAF50;` | `header`, `th` | Tạo tông màu xanh lá chủ đạo tươi sáng |
| `border-radius: 50%;` | `.avatar` | Bo tròn hoàn hảo ảnh đại diện |
| `border: 4px solid #4CAF50;` | `.avatar` | Tạo viền nổi bật cho ảnh |
| `list-style-type: square;` | `ul` | Định dạng dấu đầu dòng danh sách hình vuông |
| `border-collapse: collapse;` | `table` | Gộp đường viền kép thành viền đơn gọn gàng |
| `padding: 10px;` | `th`, `td` | Tạo khoảng cách đệm thông thoáng cho bảng |
| `text-align: center;` | `body` | Căn giữa bố cục toàn trang |
