# CBunu Static Demo

Bản này là website **tĩnh 100%** để đưa lên GitHub Pages cho client xem giao diện.

- Không có PHP.
- Không có MySQL.
- Không có `.env` hoặc mật khẩu.
- Dữ liệu demo nằm trong `assets/js/data.js`.
- Các chức năng đăng nhập, bình luận thật, tăng view/tim thật đã được vô hiệu hóa.

## Chạy local

Có thể mở `index.html` trực tiếp hoặc chạy một static server.

## Đưa lên GitHub Pages

1. Tạo một repository mới, ví dụ `cbunu-demo`.
2. Chỉ upload **nội dung của thư mục này**, không upload source PHP cũ.
3. Vào **Settings → Pages**.
4. Chọn **Deploy from a branch** → `main` → `/ (root)`.
5. GitHub sẽ cung cấp URL dạng `https://USERNAME.github.io/cbunu-demo/`.

Nếu repo demo để public thì client xem được Pages, nhưng source public cũng chỉ là HTML/CSS/JS demo và dữ liệu giả — không có secret.
