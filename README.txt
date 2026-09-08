SpaceRadiant v1.15.2 – Smart AI & Timedasher Update
================================================

Bản này phát triển từ SpaceRadiant v1.15 – Boss HUD Decorated.

TÍNH NĂNG MỚI
--------------
1. AI quái thông minh hơn
- Quái biết tránh tường và tự chọn hướng khác khi đường thẳng bị chặn.
- Một số quái có khả năng né đạn khi phát hiện đạn đang bay tới.
- AI né đạn có độ trễ vừa phải, không né quá nhanh.
- Orbit được sửa để liên tục di chuyển tự do quanh người chơi, không còn dễ mắc ở góc bản đồ.

2. Hồi phục +15%
- Mỗi lần chọn nâng cấp “+15% Hồi phục” sẽ tăng 15% cơ hội hồi 1 tim.
- Cứ mỗi 15 giây hệ thống kiểm tra một lần.
- Không hồi liên tục theo từng frame nữa.

3. Boss Phase 2
- Tất cả boss ở Phase 2 đều bắn nhanh hơn rõ rệt.
- Boss vốn thiên về đứng xa/bắn như VOID và FORTRESS cũng có thể di chuyển ở Phase 2.
- Phase 2 bắt đầu khi boss còn 50% HP.

4. Timedasher – Dasher 2.0
- Hình dạng: viên đạn.
- Tầm phát hiện khoảng 320.
- Khi phát hiện người chơi, Timedasher nhấp nháy đỏ và đếm ngược 3 → 2 → 1.
- Hết đếm ngược, nó khóa hướng và lao thẳng với tốc độ cực nhanh.
- Có khoảng thời gian cảnh báo để người chơi kịp phản ứng.
- Timedasher xuất hiện ngẫu nhiên trong các wave thường.

ĐIỀU KHIỂN TV
-------------
2 = Lên
8 = Xuống
4 = Trái
6 = Phải

Có thể giữ đồng thời hai phím hướng:
2 + 4 = chéo lên-trái
2 + 6 = chéo lên-phải
8 + 4 = chéo xuống-trái
8 + 6 = chéo xuống-phải

1 = Dash
3 = Blast

Nếu TV vẫn không nhận chéo, hãy thử dùng trình duyệt khác trên TV hoặc bàn phím/remote có gửi đồng thời keydown cho hai phím. Game vẫn giữ joystick cảm ứng.

CƠ CHẾ GAME
-----------
- 5 Wave = 1 Stage.
- Wave 5 là wave boss.
- Wave 5 có 1 boss, và có 10% cơ hội xuất hiện 2 boss.
- Boss có 6 chủ đề: Radiant, Void, Berserker, Swarm, Fortress, Phantom.
- Boss có thanh HP riêng và trang trí theo chủ đề.
- Boss Phase 2 kích hoạt ở 50% HP.
- Sau mỗi Stage có mini-game và rương thưởng.
- Khiên chặn 2 đòn.
- Có buff bắn nhanh 8 giây.

CÁCH CHẠY TRÊN TERMUX
---------------------
1. Giải nén ZIP.
2. Mở Termux.
3. Vào thư mục game, ví dụ:
   cd ~/storage/downloads/SpaceRadiant_v1_16
4. Chạy:
   python -m http.server 9999
5. Mở trên máy chạy game:
   http://127.0.0.1:9999

Máy khác cùng mạng có thể mở:
   http://IP-CUA-MAY-CHAY-SERVER:9999

LƯU Ý
-----
- Không đóng tiến trình Termux đang chạy server nếu muốn máy khác tiếp tục truy cập.
- Nếu cổng 9999 bị chiếm, hãy dừng server cũ hoặc đổi sang cổng khác.
- Đây là game chạy trực tiếp trong trình duyệt, không cần server.py.


### Lưu ý nâng cấp Hồi phục
- Nâng cấp **+15% Hồi phục** chỉ có thể chọn **1 lần** trong toàn bộ ván.
- Sau khi đã chọn, nâng cấp này sẽ không xuất hiện lại.
- Khi đã có nâng cấp, cứ mỗi 15 giây có 15% cơ hội hồi 1 HP nếu chưa đầy máu.
