Tính KPI — Supabase/PWA v19

- Sửa icon PWA trên Android: nền đen toàn khung, logo Paper World căn giữa và thu vào safe-zone để không bị crop.
- Cập nhật icon 192x192, 512x512 và favicon.
- Tăng phiên bản cache Service Worker để thiết bị nhận asset mới.
- Giữ nguyên Supabase Auth, cloud sync và toàn bộ dashboard từ v12.

Sau khi deploy lên Vercel: gỡ app Tính KPI cũ khỏi điện thoại, mở lại website bằng Chrome rồi Cài ứng dụng lại để Android lấy icon mới.


v16: Thu nhỏ logo PWA thêm 20%; sửa riêng bảng KPI trên màn hình <=600px, không thay đổi layout desktop.
v19: Đồng bộ toàn bộ phép tính theo ngày làm việc đã chốt gần nhất trước hôm nay; mọi ngày Nghỉ trong lịch được loại khỏi KPI thực tế, tốc độ, dự báo, mốc thưởng, biểu đồ, tổng kết tuần và giả lập 7 ngày. Cache PWA đã tăng lên v19.
v20: Thu gọn khu vực Giả lập KPI 7 ngày, chuyển nhập nhanh thành thanh ngang, giãn bảy ô ngày hết chiều rộng và loại các khoảng trống thừa trên desktop; giữ responsive mobile hiện tại.
v21: Thu Giả lập KPI 7 ngày về cột giữa và đặt sát dưới biểu đồ để bỏ khoảng trống do chờ cột trái; lưới ngày và phần tổng kết được thu nhỏ phù hợp chiều rộng mới.
v22: Thêm Ghi chú nhanh vào vùng trống lớn dưới bảng tuần; note tự lưu cục bộ và đồng bộ Supabase cùng dữ liệu tài khoản, có đếm ký tự và nút xóa.
v23: Thêm Lịch quay/lớp học vào vùng trống bên phải, gồm thứ, ngày, giờ và link vào lớp; hỗ trợ mở link, xóa lịch, tự lưu và đồng bộ cùng dữ liệu tài khoản.
v24: Thêm trạng thái Đã học/Chưa học cho từng lớp và tổng kết tháng gồm tổng số lớp, số đã học, số chưa học và tỷ lệ hoàn thành.


v17: Fixed mobile full-width responsive layout while preserving v16 icon and Supabase sync.
