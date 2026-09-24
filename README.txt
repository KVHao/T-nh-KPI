TÍNH KPI — PWA + SUPABASE v12

- Deploy toàn bộ thư mục này lên GitHub/Vercel.
- Đăng ký/đăng nhập bằng Email + Password qua Supabase Auth.
- KPI được đồng bộ vào bảng public.kpi_data theo user_id.
- RLS phải được bật với policy chỉ cho authenticated user truy cập user_id của chính mình.
- App vẫn giữ localStorage làm bản cục bộ và đồng bộ cloud sau khi đăng nhập.
- PWA: manifest.webmanifest + service-worker.js + icons/.

LƯU Ý BẢO MẬT:
Frontend chỉ chứa SUPABASE_URL và sb_publishable_...; không được đưa sb_secret_... vào mã nguồn.
