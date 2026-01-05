# Nhom12_GameCoCaro
🎮 Caro Online - Nhóm 12 (Project Nhóm 8)
Ứng dụng chơi cờ Caro (Gomoku) trực tuyến thời gian thực được xây dựng trên nền tảng Web, cho phép người chơi kết nối và thi đấu với nhau thông qua mã phòng.

🌟 Tính năng nổi bật
Chế độ phòng (Room-based): Tạo phòng mới với mã code ngẫu nhiên hoặc tham gia phòng hiện có.

Thời gian thực (Real-time): Mọi nước đi và trạng thái sẵn sàng được đồng bộ hóa tức thì giữa hai người chơi.

Quy trình chuyên nghiệp:

Hệ thống đặt tên người dùng.

Chế độ "Sẵn sàng" (Ready) đồng nhất từ cả hai phía trước khi bắt đầu.

Đếm ngược (Countdown) trước khi vào trận đấu.

Giao diện hiện đại: Thiết kế Responsive, hiệu ứng Gradient, và đường kẻ SVG đánh dấu chuỗi thắng cuộc.

Logic chuẩn: Bàn cờ 15x15, tự động kiểm tra thắng/thua theo luật caro cơ bản.

🛠 Công nghệ sử dụng
Frontend: - HTML5, CSS3 (Modern UI/UX).

Vanilla JavaScript (Xử lý logic Client).

Socket.io Client (Giao tiếp thời gian thực).

Backend: - Node.js

Express.js (Phục vụ file tĩnh và API).

Socket.io (Xử lý WebSocket).

🚀 Hướng dẫn cài đặt và khởi chạy
Để chạy dự án này trên môi trường local, bạn cần cài đặt sẵn Node.js.

1. Tải dự án
Bash

git clone https://github.com/vanhan812/Nhom12_GameCoCaro.git
cd Nhom12_GameCoCaro
2. Cài đặt các thư viện phụ thuộc
Dự án sử dụng Express và Socket.io. Chạy lệnh sau trong thư mục gốc:

Bash

npm install
3. Khởi động Server
Bash

npm start
Server sẽ mặc định chạy tại địa chỉ: http://localhost:3000

4. Cách chơi
Mở trình duyệt và truy cập http://localhost:3000.

Nhập tên của bạn và nhấn Tiếp tục.

Người chơi 1: Nhấn Tạo phòng mới, sau đó gửi mã phòng (ví dụ: A1B2C3) cho bạn bè.

Người chơi 2: Nhập mã phòng vào ô và nhấn Vào phòng.

Cả hai nhấn Sẵn sàng để bắt đầu trận đấu.
Để thử nghiệm chơi hai người, hãy mở thêm một cửa sổ ẩn danh khác hoặc trình duyệt khác với cùng địa chỉ trên.

Bạn có muốn tôi hỗ trợ viết thêm tệp README.md chuyên nghiệp cho dự án này để đưa lên GitHub không?
