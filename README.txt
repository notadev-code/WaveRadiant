SpaceRadiant v1.16.6 — Firebase Code System

CẤU HÌNH 1 LẦN:
1. Firebase project + Realtime Database (khu vực Singapore/asia-southeast1 là OK).
2. Bật Authentication > Sign-in method > Email/Password và tạo 1 tài khoản admin riêng cho code_tool.py.
3. Realtime Database > Rules: dùng nội dung firebase_rules.json và thay YOUR_ADMIN_EMAIL bằng email admin.
4. Chạy: python code_tool.py
5. Lần đầu nhập Database URL, Web API key, email admin và mật khẩu admin. Tool lưu cấu hình trên Termux và tự cập nhật Database URL trong index.html.
6. Upload index.html lên GitHub Pages MỘT LẦN.

SAU ĐÓ:
- Tạo code bằng code_tool.py -> code được lưu trực tiếp lên Firebase.
- Game GitHub Pages tự kiểm tra Firebase -> KHÔNG cần upload lại index.html.

BẢO MẬT:
- firebase_admin.json chứa email/mật khẩu admin sau khi cấu hình. KHÔNG upload file này lên GitHub.
- Web API key có thể xuất hiện trong cấu hình Web App; không gửi mật khẩu/private key.

SPACE RADIANT v1.17.1
- Build level-up 3 choices, combo system, random events.
- Loot: Core / Mảnh máy bay / Token. Core dùng nâng cấp máy bay; Mảnh đổi Ruby; Token mua cosmetic.
- Shop, achievements, cosmetic neon trail.
- Boss pool expanded to 10 types; boss stages remain 10,20,...,100.
- Code tool option 3 creates stage-unlock codes (unlock up to a chosen stage).


Cập nhật v1.17.7:
- Sửa lỗi màn boss: sau khi hoàn thành wave boss cuối không spawn thêm boss ngoài số wave đã quy định.
- Màn 5,15,...,95: 6 wave, mỗi wave 1 boss.
- Màn 10,20,...,90: 2 wave, mỗi wave 3 boss.
- Màn 100: 1 wave, 6 boss.

- Tăng damage quái: damage va chạm/đạn của quái thường tối thiểu 10 HP; các quái mạnh khoảng 18–22 HP.
- Damage boss tăng lên khoảng 20–35 HP tùy boss/đòn đánh, để tránh tình trạng bị trừ chỉ 1–2 HP mỗi lần.

Cập nhật v1.17.8:
- Bổ sung hiệu ứng hình ảnh rõ ràng cho kỹ năng của các máy bay.
- Skill Mark Target / Ghim quái nay có đường liên kết, vòng khóa mục tiêu và chữ GHIM trên quái bị đánh dấu.
- Thêm hiệu ứng riêng cho khiên, hồi máu, đóng băng thời gian, drone, Solar, dash, Overdrive, Missile Salvo, Time Rift, Nova, Void Burst, Meteor, Titan Blast và Chain Lightning.
- Các hiệu ứng chỉ mang tính hiển thị, giữ nguyên cơ chế gameplay hiện có.
