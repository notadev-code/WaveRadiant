SPACERADIANT v1.15 – BOSS HUD DECORATED
========================================

Game bắn quái 2D chạy trực tiếp trên trình duyệt.
Phiên bản này dựa trên SpaceRadiant v1.15 và bổ sung Boss HUD được trang trí theo chủ đề của từng Boss.


1. CÁCH CHẠY TRÊN TERMUX
-------------------------

Giải nén ZIP, sau đó chạy:

    cd ~/storage/downloads/SpaceRadiant_v1_15_BossHUD_readme
    python -m http.server 9999

Mở trình duyệt trên máy chạy server:

    http://127.0.0.1:9999

Nếu muốn máy khác cùng mạng chơi, mở:

    http://IP-CUA-MAY-CHAY-SERVER:9999

Ví dụ:

    http://192.168.1.10:9999

Không đóng Termux hoặc dừng tiến trình Python nếu vẫn muốn server hoạt động.


2. ĐIỀU KHIỂN
-------------

TV / bàn phím:

    2 = Đi lên
    8 = Đi xuống
    4 = Đi sang trái
    6 = Đi sang phải

Có thể giữ 2 phím hướng cùng lúc để di chuyển chéo:

    2 + 4 = Lên + trái
    2 + 6 = Lên + phải
    8 + 4 = Xuống + trái
    8 + 6 = Xuống + phải

    1 = Skill 1 – Dash
    3 = Skill 2 – Blast

Điện thoại vẫn có joystick cảm ứng.


3. HỆ THỐNG WAVE / STAGE
------------------------

- Mỗi Stage gồm 5 Wave.
- Wave 1 → Wave 5 hoàn thành Stage hiện tại.
- Wave 5 là Boss Wave.
- Quái thường xuất hiện lần lượt, khoảng 1 giây mỗi lần spawn.
- Số quái thường tăng theo Stage nhưng có giới hạn để tránh quá tải.
- Khi hoàn thành Stage, người chơi được hồi một phần HP và có Mini-game.
- Sau Mini-game sẽ xuất hiện Rương phần thưởng.


4. BOSS WAVE – WAVE 5
---------------------

Wave 5 chỉ có Boss, với Boss được chọn ngẫu nhiên trong 6 loại.

Có 10% cơ hội Wave 5 xuất hiện 2 Boss cùng lúc.
Nếu có 2 Boss, mỗi Boss có một thanh máu riêng.

6 loại Boss:

1) RADIANT BOSS
   Chủ đề: Ánh sáng
   Màu HUD: vàng / trắng

2) VOID BOSS
   Chủ đề: Hư vô
   Màu HUD: tím

3) BERSERKER BOSS
   Chủ đề: Cuồng nộ
   Màu HUD: đỏ

4) SWARM BOSS
   Chủ đề: Bầy đàn
   Màu HUD: vàng

5) FORTRESS BOSS
   Chủ đề: Pháo đài
   Màu HUD: xanh cyan / xanh dương

6) PHANTOM BOSS
   Chủ đề: Hư ảnh
   Màu HUD: hồng / tím


5. BOSS HUD DECORATED
----------------------

Thanh máu Boss chỉ xuất hiện trong Boss Wave (Wave 5), thay vì hiện liên tục ở các Wave thường.

Mỗi Boss có một thanh riêng với:

- Tên Boss.
- Số thứ tự #1 / #2 khi có 2 Boss.
- HP hiện tại / HP tối đa.
- Màu sắc riêng theo chủ đề Boss.
- Icon riêng.
- Khung và nền gradient.
- Hiệu ứng phát sáng.
- Nhãn chủ đề của Boss.
- Cảnh báo PHASE 2 khi Boss chuyển giai đoạn.
- Tiêu đề WAVE 5 • BOSS ENCOUNTER.


6. BOSS PHASE 2
---------------

Khi Boss còn 50% HP hoặc thấp hơn, Boss chuyển sang Phase 2.

Phase 2:

- Tốc độ Boss tăng.
- Sát thương tăng.
- Nhịp tấn công nhanh hơn.
- Có hiệu ứng cảnh báo trên màn hình.

Mỗi Boss có thanh máu riêng nên khi có 2 Boss, người chơi có thể theo dõi HP của từng con độc lập.


7. SKILL
--------

Skill 1 – Dash:
- Dùng phím 1.
- Có thời gian hồi chiêu.
- Có thể sử dụng khi đang di chuyển.

Skill 2 – Blast:
- Dùng phím 3.
- Có thời gian hồi chiêu dài hơn Skill 1.
- Có thể sử dụng khi đang di chuyển.


8. NÂNG CẤP
-----------

Khi lên Level, có thể chọn các nâng cấp như:

- Damage – tăng sát thương.
- Fire rate – tăng tốc độ bắn.
- Move speed – tăng tốc độ di chuyển.
- Max HP – tăng HP tối đa.
- Projectile – tăng số đạn.
- Range – tăng tầm bắn.
- Armor – giảm sát thương nhận vào.
- Regen – hồi HP theo thời gian.


9. HỆ THỐNG TẤN CÔNG
---------------------

- Tự động nhắm vào quái trong tầm bắn.
- Không tự bắn xuyên qua tường nếu quái bị che khuất.
- Đạn người chơi có thể phá đạn của kẻ địch.
- Có Critical Hit.
- Có thể nhận hiệu ứng Rapid Fire.


10. VẬT PHẨM HỖ TRỢ
-------------------

Có Supply Drop với các hiệu ứng:

- Khiên: chịu được 2 đòn.
- Bắn Tum Lum: Rapid Fire trong 8 giây.

Khiên không có nâng cấp trực tiếp trong danh sách Level-up.


11. RƯƠNG PHẦN THƯỞNG
---------------------

Sau khi hoàn thành Stage và Mini-game, một Rương phần thưởng xuất hiện.

Rương có thể cho ngẫu nhiên:

- +500 Score.
- +2 HP.
- Rapid Fire 8 giây.
- Khiên 2 đòn.
- +25 EXP.
- Tăng tầm bắn 10%.

Rương có thời gian tồn tại giới hạn.


12. MINI-GAME
------------

Sau mỗi Stage hoàn thành sẽ có Mini-game.

Mini-game được mở tự động sau khi qua Stage và có nhiều dạng thử thách khác nhau.


13. BẢN ĐỒ
---------

- Kích thước bản đồ: 800 × 1700.
- Player bắt đầu ở khu vực trung tâm.
- Có tường làm vật cản.
- Quái được spawn tại vị trí an toàn, tránh tường.
- Các đối tượng quan trọng được giới hạn trong bản đồ.


14. CÁC LOẠI QUÁI
-----------------

Quái thường gồm nhiều kiểu với hình dạng và hành vi khác nhau, ví dụ:

- Melee
- Ranged
- Chaser
- Ring Shooter
- Speed Shooter
- Tanker
- Sniper
- Dasher
- Splitter
- Mine Layer
- Orbit
- Healer
- Turret
- Shard

Splitter có thể tách thành Shard khi bị tiêu diệt.


15. LƯU Ý KHI CHƠI TRÊN TV
---------------------------

- Nên mở game ở chế độ ngang (landscape).
- TV cần hỗ trợ bàn phím / remote gửi phím số để dùng điều khiển 2/8/4/6 và 1/3.
- Nếu TV không nhận phím số, có thể dùng joystick cảm ứng trên thiết bị có hỗ trợ cảm ứng.
- Nếu màn hình cũ không hỗ trợ một số hiệu ứng Canvas, game có cơ chế vẽ tương thích để hạn chế lỗi.


16. PHIÊN BẢN
-------------

Tên: SpaceRadiant v1.15 – Boss HUD Decorated
Nền: SpaceRadiant v1.15
Thay đổi chính của bản này: Boss HUD được thiết kế lại theo chủ đề từng Boss và chỉ hiển thị ở Wave 5.

