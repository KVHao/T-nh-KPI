Tính KPI — Supabase v13 Icon Fix

- Sửa icon PWA trên Android: nền đen toàn khung, logo Paper World căn giữa và thu vào safe-zone để không bị crop.
- Cập nhật icon 192x192, 512x512 và favicon.
- Tăng phiên bản cache Service Worker để thiết bị nhận asset mới.
- Giữ nguyên Supabase Auth, cloud sync và toàn bộ dashboard từ v12.

Sau khi deploy lên Vercel: gỡ app Tính KPI cũ khỏi điện thoại, mở lại website bằng Chrome rồi Cài ứng dụng lại để Android lấy icon mới.


Version v15: Restored original desktop KPI table layout; mobile-only width safeguards remain scoped to <=620px.
