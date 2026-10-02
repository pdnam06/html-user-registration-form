# Form đăng ký người dùng

Bài thực hành tạo form đăng ký và gửi dữ liệu đến endpoint mẫu của CodeGym.

## Cấu hình gửi dữ liệu

- Action: `http://demo.codegym.vn/6/registration_form/register.php`
- Method: `POST`

## Các trường

- Họ và tên: `name="name"`
- Email: `name="email"`
- Số điện thoại: `name="phone"`
- Giới tính: các radio button sử dụng chung `name="gender"`

Endpoint là máy chủ mẫu phục vụ bài thực hành nên có thể không còn hoạt động hoặc trả về lỗi.

Ảnh chụp kết quả nằm tại `screenshots/form-dang-ky-nguoi-dung.png`.
