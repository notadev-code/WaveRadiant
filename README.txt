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
