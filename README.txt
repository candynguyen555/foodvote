FOODVOTE — HƯỚNG DẪN CÀI ĐẶT

1. Mở index.html và admin.html.
2. Tìm:
   YOUR_SUPABASE_URL
   YOUR_SUPABASE_PUBLISHABLE_KEY
3. Thay bằng Project URL và Publishable key của dự án Supabase Foodvote.
   KHÔNG dùng Secret key.
4. Lưu hai file.
5. Đưa index.html, admin.html lên GitHub Pages.
6. supabase.sql chỉ dùng nếu bạn cần tạo lại database. Database của dự án hiện đã được tạo rồi.

Đăng nhập quản trị:
- Dùng tài khoản email/password bạn đã tạo trong Supabase Authentication → Users.
- admin.html dùng tài khoản đó để thêm/ẩn nhà hàng.

LƯU Ý BẢO MẬT:
- Publishable key có thể xuất hiện trong website.
- Tuyệt đối không đưa Secret/service_role key vào HTML.
- Bản này có chống bấm lại bằng localStorage ở mức cơ bản. Người dùng có thể xóa dữ liệu trình duyệt/đổi thiết bị.
- RLS hiện cho phép mọi tài khoản authenticated thêm/cập nhật nhà hàng. Trước khi đưa vào sử dụng rộng rãi nên giới hạn quyền admin theo tài khoản admin.
