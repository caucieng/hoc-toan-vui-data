# Hướng Dẫn Upload Dữ Liệu Lên GitHub Pages

Repo cần upload:

https://github.com/caucieng/hoc-toan-vui-data

## Cách làm nhanh bằng trình duyệt

1. Mở repo trên GitHub và đăng nhập tài khoản `caucieng`.
2. Bấm `Add file` -> `Upload files`.
3. Kéo thả các file/thư mục trong thư mục này lên GitHub:
   - `.nojekyll`
   - `README.md`
   - `index.html`
   - `manifest.json`
   - thư mục `data`
4. Bấm `Commit changes`.
5. Vào `Settings` -> `Pages`.
6. Ở `Build and deployment`, chọn:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
7. Bấm `Save`.

Sau vài phút, kiểm tra link:

https://caucieng.github.io/hoc-toan-vui-data/manifest.json

Nếu link này mở ra thấy nội dung JSON là app có thể cập nhật bài học.

## Lưu ý quan trọng

Repo này là công khai. Chỉ để dữ liệu bài học/câu hỏi/bài tập ở đây.
Không đưa thông tin học sinh, điểm số, lịch sử làm bài hoặc dữ liệu cá nhân lên repo này.
