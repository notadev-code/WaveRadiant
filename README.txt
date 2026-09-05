SpaceRadiant v1.4

Bản này chốt các thay đổi cho TV và map:

- World: 1000 x 2750.
- Bố cục tường được thiết kế lại hoàn toàn để nằm trong map 1000 x 2750.
- Loại bỏ các tường có tọa độ cũ vượt khỏi map.
- Giữ hệ thống Range và nâng cấp Range +20% của v1.2/v1.3.
- Điều khiển TV/bàn phím:
  8 = lên
  2 = xuống
  4 = trái
  6 = phải
  Giữ 2 phím hướng cùng lúc = đi chéo.
  1 = Skill 1 (Dash)
  3 = Skill 2 (Blast)
- Giao diện responsive, ưu tiên bố cục ngang khi màn hình rộng/TV.
- Joystick cảm ứng vẫn được giữ cho điện thoại.

Chạy Termux:
  cd ~/storage/downloads/SpaceRadiant_v1_4
  python -m http.server 9999 --bind 127.0.0.1

Mở:
  http://127.0.0.1:9999/index.html


SpaceRadiant v1.4.1: Fixed Orbit enemy leaving the map. Only Orbit boundary handling was changed.
