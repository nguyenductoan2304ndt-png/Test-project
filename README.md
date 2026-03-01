# Test-project
Không có gì miêu tả ở đây cả :)))
1. 🎯 Phân Công Nhiệm Vụ Rõ Ràng
Để tránh dẫm chân lên nhau khi code, dự án được chia làm 3 mảng độc lập. Mỗi người làm tốt phần của mình, sau đó ráp lại:

👨‍🎨 Thành viên 1 (Tên của bạn) - UI/UX, Đồ họa & Game Feel: * Chịu trách nhiệm toàn bộ phần nhìn và cảm giác chơi.

Thiết kế hoặc tìm kiếm hình ảnh (nhân vật, vật thể rơi, background), font chữ, âm thanh.

Xây dựng bố cục màn hình Start Menu, Game Over.

Vận dụng tư duy thẩm mỹ và trải nghiệm chơi game để tinh chỉnh màu sắc, đảm bảo game trông thuận mắt và mượt mà nhất.

👨‍💻 Thành viên 2 (Bạn IT 1) - Core Engine & Player Logic:

Thiết lập cửa sổ game và vòng lặp chính (Game Loop) bằng thư viện (vd: Raylib).

Xử lý logic di chuyển của nhân vật (cái giỏ) qua trái/phải.

Giới hạn khung hình để nhân vật không đi xuyên tường hoặc lọt ra ngoài màn hình.

👨‍💻 Thành viên 3 (Bạn IT 2) - Object Logic & Hệ thống Điểm:

Viết logic sinh ra vật thể rơi ngẫu nhiên từ trên xuống với tốc độ khác nhau.

Xử lý toán học cho va chạm (Collision): Khi nào rổ chạm vào đồ.

Làm hệ thống cộng điểm khi ăn trúng đồ tốt, trừ điểm/mất máu khi ăn trúng bom.

2. 🤝 Văn Hóa & Quy Tắc Team
Ưu tiên logic, không toxic: Quá trình làm chắc chắn sẽ có lúc code bị lỗi (bug) hoặc gộp code bị xung đột (conflict). Anh em đề cao sự hòa bình, cứ bình tĩnh ngồi lại phân tích logic để tìm nguyên nhân chứ không tranh cãi.

Code sạch & Chú thích (Comment): Viết code dễ đọc một chút, nhớ thêm chú thích (comment) vào những đoạn logic khó để hai người kia đọc vào còn hiểu bạn đang viết cái gì.

3. 🔄 Quy Trình Làm Việc Trên GitHub (BẮT BUỘC)
Chúng ta sẽ quản lý task bằng GitHub Projects (Kanban Board) dạng cột: To Do (Cần làm) -> In Progress (Đang làm) -> Done (Hoàn thành).

Luồng làm việc chuẩn mỗi khi ngồi vào máy:

Nhận việc: Lên bảng Kanban, chọn 1 task ở cột To Do, kéo sang In Progress và gán tên mình vào.

Đồng bộ: Mở terminal, gõ git pull origin develop để lấy code mới nhất của cả nhóm về máy mình.

Cắt nhánh riêng: Tuyệt đối không code thẳng lên nhánh main hay develop. Tạo nhánh riêng cho tính năng mình sắp làm.

Cú pháp: git checkout -b feature/ten-task-cua-ban (VD: feature/menu-ui hoặc feature/player-move).

Code & Lưu vết: Làm xong task, lưu lại với mô tả rõ ràng:

git add .

git commit -m "Thêm hình ảnh rổ và background"

Đẩy lên GitHub: git push origin feature/ten-task-cua-ban.

Tạo Pull Request (PR): Lên GitHub, bấm tạo PR yêu cầu gộp nhánh của bạn vào nhánh develop.

Review (Duyệt code): Báo lên group chat. 1 trong 2 người còn lại sẽ vào xem code, chạy thử. Nếu ổn thì bấm Merge. Done! Kéo thẻ task sang cột Done.

4. 🗺️ Lộ Trình Triển Khai (Milestones)
📍 Bước 1: Khởi động (Setup)

Cả 3 clone repo về máy.

Cài đặt thành công thư viện C/C++. Chạy thử lên được một cửa sổ trắng là thành công.

📍 Bước 2: Khung xương (Prototype)

Chưa cần hình ảnh đẹp. Dùng các hình khối cơ bản (vuông, tròn) để làm.

Mục tiêu: Rổ di chuyển được, đồ rơi xuống được, hứng trúng đồ thì điểm nhảy.

📍 Bước 3: Đắp da đắp thịt (Polishing)

Đưa hình ảnh (assets) vào thay thế các hình khối.

Ghép màn hình Menu, Game Over vào.

Cân bằng game: Tăng tốc độ rơi khi điểm cao lên để game thử thách hơn.

📍 Bước 4: Hoàn thiện & Đóng gói

Fix các lỗi lặt vặt (bug).

Đóng gói (build) ra file .exe để gửi cho bạn bè chơi thử.
