SpaceRadiant v1.16.6 — Firebase Code System

1. Tạo Firebase project + Realtime Database + Web App.
2. Bật Email/Password trong Firebase Authentication và tạo 1 tài khoản admin riêng cho code_tool.py.
3. Trong Realtime Database Rules, dùng firebase_rules.json và thay YOUR_ADMIN_EMAIL bằng email admin.
4. Chạy: python code_tool.py
5. Lần đầu nhập Database URL, Web API key, email admin, mật khẩu. Tool tự ghi Database URL vào index.html.
6. Upload index.html lên GitHub Pages một lần.
7. Về sau tạo code bằng code_tool.py: code lưu trực tiếp Firebase, game GitHub Pages tự kiểm tra — không upload HTML lại.

firebase_admin.json chứa mật khẩu admin, KHÔNG upload file này lên GitHub.
