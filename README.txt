Tính KPI — Supabase v13 Icon Fix

- Sửa icon PWA trên Android: nền đen toàn khung, logo Paper World căn giữa và thu vào safe-zone để không bị crop.
- Cập nhật icon 192x192, 512x512 và favicon.
- Tăng phiên bản cache Service Worker để thiết bị nhận asset mới.
- Giữ nguyên Supabase Auth, cloud sync và toàn bộ dashboard từ v12.

Sau khi deploy lên Vercel: gỡ app Tính KPI cũ khỏi điện thoại, mở lại website bằng Chrome rồi Cài ứng dụng lại để Android lấy icon mới.


v16: Thu nhỏ logo PWA thêm 20%; sửa riêng bảng KPI trên màn hình <=600px, không thay đổi layout desktop.
