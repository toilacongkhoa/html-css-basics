# Cấu trúc HTML cơ bản (`index.html`)

- `<!DOCTYPE html>`: Định nghĩa loại tài liệu (đặt ở đầu file).
- `<html>`: Chứa toàn bộ nội dung (chỉ 1 thẻ duy nhất).
- Bên trong `<html>` gồm:
  - `<head>`: Chứa thông tin trang (`<title>`: tiêu đề, `<meta charset="utf-8">`: hỗ trợ tiếng Việt).
  - `<body>`: Chứa nội dung hiển thị chính. Các thẻ con thường dùng:
    - `<h1>` đến `<h6>`: Tiêu đề (cỡ chữ nhỏ dần, có thẻ thêm `title` hiện tooltip khi trỏ chuột).
    - `<p>`: Đoạn văn bản.
    - `<img>`: Hiển thị ảnh (`src`: nguồn ảnh, `alt`: text thay thế khi lỗi ảnh).
    - `<a>`: Liên kết (`href`: đường dẫn đích).
    - `<ul>` & `<li>`: Danh sách (`<ul>` chứa nhiều `<li>`).
    - `<table>`: Tạo bảng (`<thead>` chứa `<th>` làm tiêu đề cột; `<tbody>` chứa các dòng `<tr>`, trong `<tr>` chứa các ô nội dung `<td>`).
    - `<input>`: Nhập liệu (VD: `type="text"`, `type="checkbox"`, `type="radio"` - nhóm cùng `name` sẽ chỉ chọn 1).
    - `<button>`: Tạo nút bấm.
    - `<div>`: Tạo khối bao bọc các thẻ khác.