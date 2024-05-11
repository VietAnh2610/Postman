## Giới thiệu

Repository này chứa các trường hợp kiểm thử và kết quả cho việc kiểm thử API bằng Postman. Mục tiêu chính là đảm bảo tính năng và độ tin cậy của các điểm cuối của API. Readme này cung cấp thông tin về các trường hợp kiểm thử đã thực hiện, kết quả của chúng, và các khuyến nghị để cải thiện.

# Báo cáo Kiểm thử API

## Mục tiêu

Mục tiêu của báo cáo này là kiểm thử các chức năng chính của API để đảm bảo tính ổn định và đáng tin cậy của hệ thống.

## Phạm vi Kiểm thử

Các chức năng chính của API được kiểm thử bao gồm:

1. Đăng ký tài khoản mới (PostRegister).
2. Đăng nhập (PostLogin).
3. Xử lý yêu cầu với thời gian trễ (DELAYED RESPONSE).
4. Lấy thông tin người dùng bằng ID (GET User by ID).
5. Cập nhật thông tin người dùng bằng ID (PUT User by ID).
6. Cập nhật một phần thông tin người dùng bằng ID (PATCH User by ID).
7. Xóa người dùng bằng ID (DELETE User by ID).

## Kết quả Kiểm thử

Dưới đây là kết quả kiểm thử:

- PostRegister: Yêu cầu thành công với mã trạng thái 200.
- PostLogin: Yêu cầu thành công với mã trạng thái 200.
- DELAYED RESPONSE: Yêu cầu thành công với mã trạng thái 200 và thời gian phản hồi là ít nhất 3 giây.
- GET User by ID: Yêu cầu thành công với mã trạng thái 200 và thông tin người dùng chính xác.
- PUT User by ID: Yêu cầu thành công với mã trạng thái 200 hoặc 204 và thông tin người dùng được cập nhật chính xác.
- PATCH User by ID: Yêu cầu thành công với mã trạng thái 200 hoặc 204 và thông tin người dùng được cập nhật chính xác.
- DELETE User by ID: Yêu cầu thành công với mã trạng thái 204.

![image](https://github.com/VietAnh2610/Postman/assets/129382437/da9d825e-a347-4dc0-8fe1-bf04bba0fba9)

## Khuyến nghị

Dựa trên kết quả kiểm thử, dưới đây là các khuyến nghị:

1. Xác thực dữ liệu đầu vào và xử lý lỗi một cách hợp lý khi đăng ký tài khoản mới và đăng nhập.
2. Đảm bảo hệ thống có khả năng xử lý yêu cầu với thời gian trễ một cách hiệu quả.
3. Xác thực thông tin đăng nhập và xử lý lỗi một cách hợp lý khi đăng nhập.
4. Xác thực ID người dùng và xử lý lỗi một cách hợp lý khi lấy thông tin, cập nhật hoặc xóa người dùng.


## Liên hệ

Nếu có bất kỳ thắc mắc hoặc góp ý nào, vui lòng liên hệ:

- Tên: Việt Anh
- Email: 20010695@st.phenikaa-uni.edu.vn

