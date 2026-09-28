# Đúc Kết

Blog cá nhân ghi lại nội dung đã đọc, đã học, và đúc kết lại — dựng bằng
Jekyll, xuất bản qua GitHub Pages.

## Cách vận hành

- Mỗi bài viết là một file Markdown trong `_posts/`, đặt tên theo định dạng
  `NĂM-THÁNG-NGÀY-tieu-de.md`.
- GitHub Pages tự build Jekyll phía server khi push code lên — không cần cài
  Ruby/Jekyll ở máy, không cần chạy `jekyll serve` để xem trước.
- Xem hướng dẫn viết bài chi tiết trong bài đăng đầu tiên: `_posts/2026-09-25-chao-mung.md`.

## Giao diện

Layout và CSS tự viết riêng (`_layouts/`, `assets/css/style.css`), theo đúng
quy ước thiết kế chung của các trang khác: font hệ thống, thẻ (card) phẳng
viền 1px, bo góc 14px, hỗ trợ cả giao diện sáng/tối theo
`prefers-color-scheme`. Màu nhấn tím indigo (`#6c5ce7` / `#a29bfe` ở chế độ
tối) — không trùng màu với app nào khác.
