T-NH KPI PWA v8

Cách đưa lên Vercel/GitHub:
1. Giải nén ZIP.
2. Đưa TOÀN BỘ file/thư mục trong gói lên thư mục gốc của repository đang deploy trên Vercel.
3. Giữ nguyên cấu trúc: index.html, manifest.webmanifest, service-worker.js, icons/.
4. Chờ Vercel deploy xong rồi mở website bằng Chrome hoặc Edge.
5. Bấm nút "Tải app" cạnh "Xuất dữ liệu" để cài.

Lưu ý:
- PWA cần chạy qua HTTPS; Vercel có HTTPS sẵn.
- Nếu vừa deploy mà nút chưa cài được, refresh trang một lần để service worker/manifest được nhận.
