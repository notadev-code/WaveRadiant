SPACE RADIANT v1.17.10

CẬP NHẬT v1.17.10
- Cửa hàng: vật phẩm chỉ mua 1 lần nay sau khi mua sẽ hiện "ĐÃ MUA" và nút bị khóa.
- Nâng cấp máy bay: khi đạt Lv25 sẽ hiện "⭐ TỐI ĐA"; không thể mua vượt cấp.
- Boss HUD: thu nhỏ thanh máu, tự chia nhiều boss thành lưới để không che khuất màn hình; đặc biệt gọn khi có 3 hoặc 6 boss.
- HP player: đổi từ số dạng 00/00 sang thanh HP màu xanh lá.
- MP player: đổi từ số dạng 00/00 sang thanh MP màu xanh nước biển.
- Skill 1 giảm từ 20 MP xuống 10 MP.
- Skill 2 giảm từ 35 MP xuống 20 MP.
- Bổ sung hình dạng riêng cho Gravity Boss, Inferno Boss, Chrono Boss và Abyss Boss.
- Giữ nguyên Firebase, tài khoản, save, mã code và các hệ thống gameplay trước đó.

CÁC QUÁI THƯỜNG
1. Melee — hình bọ/cua đỏ có 2 càng — cận chiến.
2. Ranged — UFO/đĩa bay — bắn đạn tầm xa.
3. Chaser — mũi giáo — lao/đuổi theo người chơi, đạn có xu hướng bám mục tiêu.
4. Ring Shooter — đĩa bay có vòng — bắn vòng 8 hướng.
5. Speed Shooter — tia sét — di chuyển nhanh, bắn đạn nhanh.
6. Tanker — xe tăng bọc giáp — rất nhiều HP, áp sát gây sát thương.
7. Sniper — súng/bệ ngắm — bắn tỉa chậm, đạn mạnh.
8. Dasher — phi tiêu 2 cánh — tích lực rồi dash nhanh về phía người chơi.
9. Timedasher — viên đạn/phi tiêu đỏ — khóa hướng người chơi rồi dash cực nhanh.
10. Splitter — tinh thể xanh nứt — khi chết tạo 2 Shard.
11. Mine Layer — quả mìn gai — đặt mìn trên bản đồ.
12. Orbit — lõi nguyên tử có 3 vòng — bay quanh người chơi và bắn đạn theo quỹ đạo.
13. Healer — tinh thể dấu cộng — hồi máu cho quái đồng minh gần đó.
14. Turret — robot tháp pháo — đứng tương đối xa và bắn chùm 3 viên.
15. Shard — mảnh tinh thể — con nhỏ sinh ra từ Splitter, áp sát.
16. Leech — sinh vật hút máu — áp sát để gây sát thương.
17. Bomber — khối bom — áp sát/tiếp cận để gây sát thương lớn.
18. Frost — tinh thể băng — đánh tầm xa.
19. Teleporter — tinh thể/dạng dịch chuyển — di chuyển linh hoạt và bắn tầm xa.
20. Laserer — pháo/laser — tầm bắn rất xa, được Tanker/Shielded hỗ trợ che chắn.
21. Swarm Drone — drone nhỏ — di chuyển rất nhanh và áp sát.
22. Shielded — khối giáp — HP cao, đóng vai trò che chắn cho quái tầm xa.

BOSS
1. RADIANT BOSS — mặt trời nhiều tia — bắn vòng đạn lan tỏa.
2. VOID BOSS — mắt/hố đen — bắn 3 đạn tầm xa, đạn lớn và khó chặn.
3. BERSERKER BOSS — chiến binh/rìu gai — bắn chùm 3 đạn và di chuyển nhanh.
4. SWARM BOSS — tổ ong/bầy đàn — bắn 6 đạn tỏa ngẫu nhiên.
5. FORTRESS BOSS — pháo đài — bắn chùm 7 đạn.
6. PHANTOM BOSS — bóng ma — bắn 4 đạn theo các hướng/quỹ đạo.
7. GRAVITY BOSS — lõi trọng lực với các vòng xoắn — bắn 8 đạn có khả năng bám hướng.
8. INFERNO BOSS — ngọn lửa — bắn chùm 9 đạn hình quạt.
9. CHRONO BOSS — đồng hồ — bắn 5 đạn có khả năng bám hướng.
10. ABYSS BOSS — ngôi sao/hố vực thẳm — bắn 12 đạn tỏa tròn, đạn lớn cần 2 phát để chặn.

TẤT CẢ BOSS đều có 3 phase:
- Phase 1: bình thường.
- Phase 2: nhanh hơn, sát thương/tốc độ bắn tăng.
- Phase 3: nhanh hơn nữa và có thêm đợt đạn.

CHẠY LOCAL
- Mở Termux trong thư mục game.
- python server.py (nếu thư mục có server.py)
- Hoặc python -m http.server 9999 --bind 127.0.0.1
- Mở http://127.0.0.1:9999

Firebase/code system vẫn giữ nguyên theo bản trước.


SpaceRadiant v1.17.10 updates:
- Fixed wave transition so normal waves advance correctly and boss stages spawn bosses reliably.
- Boss waves are completed only after all intended bosses are defeated.
- Shop Core upgrades now add +10 levels per purchase, and can exceed the normal Lv25 upgrade display (e.g. 35/25).
- HP and MP keep visual bars and now also show numeric counters beside them (00/00 format).
