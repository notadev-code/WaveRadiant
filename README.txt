SpaceRadiant v1.16.3 – fixed

Các cập nhật:
- Stage: khi hoàn thành màn sẽ dừng game và hiện Victory.
- Victory hiển thị thưởng lần đầu theo từng màn (500 Gold, chỉ nhận 1 lần), thưởng vượt màn, tổng thưởng và thông báo mở màn tiếp theo.
- Victory có 3 nút: Về menu, Chơi lại, Qua màn. Màn 100 sẽ báo hoàn thành toàn bộ và ẩn nút Qua màn.
- Chơi lại không nhận lại thưởng lần đầu; thưởng vượt màn vẫn được nhận khi hoàn thành lại.
- Tool tạo code đã sửa lỗi code tạo ra nhưng game không nhận: regex nhập code 8 số và cơ chế đồng bộ REDEEM_CODES đã được sửa.
- Có sẵn codes.json để code_tool.py chạy ngay và không làm mất 2 code mặc định.
- Nút Đăng xuất trong Cài đặt đã được gắn sự kiện click/touch.

Chạy game: mở index.html.
Chạy tool: python3 code_tool.py
