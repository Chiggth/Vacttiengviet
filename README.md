# V-ACT Tiếng Việt

Website tĩnh luyện thi V-ACT bằng tiếng Việt, thiết kế theo `input/DESIGN.md`.

## Chạy và đăng website

Mở `index.html` trực tiếp hoặc đẩy các file `index.html`, `styles.css`, `app.js`, `extracted-theory.md` lên GitHub. Trong GitHub, vào **Settings → Pages**, chọn nhánh và thư mục gốc để xuất bản.

## Nội dung và tính năng

- 8 chuyên đề được hệ thống hóa từ tài liệu OCR ở `input/phan-1.md` đến `input/phan-8.md`; bản trích lọc có ghi chú nguồn và giới hạn OCR trong `extracted-theory.md`.
- Ví dụ minh họa cho từng chuyên đề, ôn tập nhanh và bài trắc nghiệm có giải thích.
- Trợ lý hỏi đáp/tạo câu hỏi ở chế độ demo. Để gọi AI thật, cần xây dựng backend proxy và cấu hình khóa API phía máy chủ; không nhúng khóa bí mật vào website tĩnh.

## Cấu trúc

- `index.html`, `styles.css`, `app.js`: website
- `extracted-theory.md`: nội dung lý thuyết trích lọc
