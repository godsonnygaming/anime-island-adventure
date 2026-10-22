# Anime Island Adventure

Một game phiêu lưu RPG 2D chạy trên trình duyệt, lấy cảm hứng từ thể loại anime đảo và luyện cấp nhưng dùng tên, bản đồ và nội dung nguyên bản.

## Chạy trên máy Windows
1. Cài Node.js phiên bản 20 trở lên.
2. Giải nén thư mục này.
3. Mở Terminal/CMD trong thư mục có `package.json`.
4. Chạy `npm install`
5. Chạy `npm start`
6. Mở http://localhost:3000

## Deploy lên Render
- Tạo Web Service từ repository GitHub.
- Root Directory: để trống nếu package.json ở thư mục gốc; nếu nằm trong thư mục con thì nhập tên thư mục đó.
- Build Command: `npm install`
- Start Command: `npm start`
- Runtime: Node

## Điều khiển
- WASD hoặc phím mũi tên: di chuyển
- Space: chém kiếm
- E: Hỏa cầu
- Nút nhiệm vụ: nhận nhiệm vụ hạ 5 quái
- Hồi phục: tốn 20 xu để hồi 50 HP

## Lưu ý
Đây là bản MVP một người chơi, chưa có multiplayer, tài khoản, database hoặc lưu tiến trình. Không dùng tên, hình ảnh, nhân vật hay tài sản có bản quyền của Blox Fruits.
