# HDSD Wework & Account - Green i-Park (bản công khai, không mật khẩu)

Trang tĩnh gồm 1 file `index.html` (đã nhúng sẵn toàn bộ ảnh) và `vercel.json`.
Không có `middleware.js`, không cần biến môi trường, không hỏi mật khẩu.

## Triển khai
1. GitHub: tạo repo (Private cũng được), tải lên `index.html` và `vercel.json` ở thư mục gốc.
2. Vercel: Add New > Project > chọn repo > Framework Preset: **Other** > Deploy.
3. Nếu dự án Vercel cũ còn bật **Deployment Protection** (Settings > Deployment Protection), chọn tắt (Disabled) để ai có link cũng mở được.

Cập nhật nội dung: ghi đè `index.html` trong repo, Vercel tự deploy lại.
