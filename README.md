# AURORA — K-pop Visual Archive

Website tĩnh (HTML/CSS/JavaScript) — không cần cài đặt, không có backend hay cơ sở dữ liệu. Có thể host miễn phí trực tiếp.

## Cách nhanh nhất: Netlify Drop

1. Mở [app.netlify.com/drop](https://app.netlify.com/drop) và đăng nhập miễn phí.
2. Kéo thả toàn bộ thư mục dự án này (`aurora`) vào trang Netlify Drop.
3. Netlify sẽ tạo ngay một đường link công khai. Có thể đổi tên link trong **Site configuration → Change site name**.

Lưu ý: khi kéo thả, phải bao gồm cả `index.html` và thư mục `hình ảnh` để lookbook hiển thị đúng.

## Cách ổn định: GitHub Pages

1. Tạo một repository mới trên GitHub, ví dụ `aurora-archive`.
2. Upload toàn bộ các tệp và thư mục trong dự án này lên repository (giữ nguyên cấu trúc thư mục `hình ảnh`).
3. Trong repository, vào **Settings → Pages**.
4. Chọn **Deploy from a branch**, chọn nhánh `main` và thư mục `/(root)`, rồi lưu.
5. Sau vài phút, website có tại `https://<tên-github>.github.io/aurora-archive/`.

## Lưu ý khi chỉnh sửa

- Trang bắt đầu tại `index.html`.
- Ảnh nằm trong thư mục `hình ảnh`; không đổi tên hoặc di chuyển ảnh đã được dùng trong trang nếu chưa sửa lại đường dẫn trong HTML.
- Có thể mở `index.html` bằng trình duyệt để xem trước trước khi đăng lên host.
