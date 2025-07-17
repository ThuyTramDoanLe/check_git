# Test Case: TC001 - Kiểm thử chức năng Đăng nhập

## Mục đích
Kiểm tra chức năng đăng nhập với tài khoản hợp lệ và không hợp lệ.

## Điều kiện đầu vào
- Người dùng đã có tài khoản hợp lệ trên hệ thống.
- Truy cập trang đăng nhập của ứng dụng.

## Các bước thực hiện

| Bước | Mô tả hành động                         | Dữ liệu nhập                 | Kết quả mong đợi                  |
|-------|---------------------------------------|-----------------------------|----------------------------------|
| 1     | Mở trang đăng nhập                    |                             | Trang đăng nhập hiển thị          |
| 2     | Nhập tên đăng nhập hợp lệ             | username: `user123`          |                                  |
| 3     | Nhập mật khẩu hợp lệ                   | password: `password123`      |                                  |
| 4     | Nhấn nút "Đăng nhập"                  |                             | Chuyển đến trang Dashboard       |
| 5     | Đăng xuất và quay lại trang đăng nhập |                             | Trang đăng nhập hiển thị          |
| 6     | Nhập tên đăng nhập không hợp lệ       | username: `wronguser`        |                                  |
| 7     | Nhập mật khẩu không hợp lệ             | password: `wrongpass`        |                                  |
| 8     | Nhấn nút "Đăng nhập"                  |                             | Hiện thông báo lỗi "Sai tên đăng nhập hoặc mật khẩu" |

## Kết quả thực tế
(Điền sau khi test)

## Trạng thái
(Đỗ / Rớt)

## Ghi chú
- Đảm bảo tài khoản test hợp lệ đã được tạo trước khi thực hiện.
hello 
