GALAXY CRUSH — BẢN TỐI ƯU CHIA SẺ INSTAGRAM

1) Cá nhân hóa:
   Mở index.html và tìm CONFIG ở cuối file:
   crushName: "em"     -> có thể đổi thành tên thật, ví dụ "Linh"
   fromName: "Anh"     -> có thể đổi thành tên của bạn, ví dụ "Hùng"

2) Chạy thử trên máy:
   Mở index.html bằng Chrome/Edge/Safari.
   Nhạc chỉ bắt đầu sau khi người xem bấm nút, đúng quy định autoplay của trình duyệt di động.

3) Để gửi qua Instagram:
   Website phải có URL công khai dạng https://...

   NETLIFY DROP:
   - Vào Netlify Drop.
   - Kéo THƯ MỤC galaxy_crush vào trang upload (không kéo riêng index.html).
   - Netlify cấp một URL https://...netlify.app.
   - Gửi URL đó qua Instagram DM hoặc dùng Link Sticker trong Story.

   VERCEL:
   - Tạo project mới và upload/import thư mục này.
   - Framework Preset: Other.
   - Không cần build command.
   - Output directory: để trống / root.

4) Nút "Chia sẻ đường link":
   Khi website đã deploy, nút này dùng Web Share của điện thoại. Nếu thiết bị không hỗ trợ,
   trang sẽ cố sao chép URL vào clipboard để bạn dán vào Instagram.

5) Quyền riêng tư:
   Trang đã đặt robots=noindex,nofollow để giảm khả năng bị công cụ tìm kiếm lập chỉ mục.
   Tuy nhiên ai có link vẫn có thể mở trang. Muốn giới hạn truy cập bằng mật khẩu thì cần bổ sung lớp bảo vệ riêng.

