# Dự Án Website Thương Mại Điện Tử

## Tổng Quan
Dự án này phát triển một nền tảng thương mại điện tử với nhiều tính năng nhằm mang lại trải nghiệm mua sắm trực tuyến mượt mà. Website cho phép người dùng duyệt và mua sản phẩm, quản lý giỏ hàng và xử lý giao dịch với nhiều cửa hàng hiệu quả. Ngoài ra, hệ thống còn cung cấp các tính năng như phân loại sản phẩm, quản lý người dùng, xử lý đơn hàng và hệ thống thanh toán thông minh.

## Thành Viên Nhóm

| **Họ Tên**              | **Mã Số Sinh Viên** |
|-------------------------|---------------------|
| Nguyễn Công Quý        | 22110403            |
| Lương Quang Thịnh      | 22110428            |
| Nguyễn Đức Sang        | 22110404            |
| Phạm Tiến Anh          | 22110282            |
| Nguyễn Hoàng Thùy Linh | 22110364            |

## Tính Năng Dự Án

1. **Quản Lý Sản Phẩm**
   - Thêm, sửa, xóa và xem sản phẩm.
   - Phân loại sản phẩm theo loại, thương hiệu và khoảng giá.

2. **Quản Lý Người Dùng**
   - Đăng ký và đăng nhập người dùng.
   - Phân quyền (ví dụ: quản trị viên, khách hàng) với các quyền hạn cụ thể.

3. **Giỏ Hàng và Thanh Toán**
   - Thêm/xóa sản phẩm khỏi giỏ hàng.
   - Chia nhỏ hóa đơn cho các giao dịch từ nhiều cửa hàng.
   - Tích hợp cổng thanh toán an toàn.

4. **Quản Lý Đơn Hàng và Kho Hàng**
   - Theo dõi trạng thái đơn hàng (ví dụ: đang xử lý, đã giao hàng).
   - Giám sát số lượng hàng tồn kho và thông báo khi sắp hết hàng.

5. **Đánh Giá và Xếp Hạng**
   - Cho phép người dùng để lại đánh giá và xếp hạng sản phẩm.


## Công Nghệ Sử Dụng

- **Frontend**: HTML5, CSS3 - SCSS (Bootstrap / TailwindCSS), JavaScript (React).
- **Backend**: Java (Spring Framework: Spring Boot, Spring Security, Spring Clound).
- **Cơ Sở Dữ Liệu**: MySQL / Redis.
- **Quản Lý Phiên Bản**: GitHub.
- **Triển Khai**: Docker / K8S.

## Cách Chạy Dự Án

1. Clone repository:
   ```bash
   git clone https://github.com/repo----
   ```
2. Di chuyển đến thư mục dự án và thiết lập backend:
   ```bash
   cd backend
   mvn clean install
   ```
3. Khởi chạy server:
   ```bash
   mvn spring-boot:run
   ```
4. Thiết lập frontend:
   ```bash
   cd frontend
   npm install
   npm start
   ```
5. Truy cập ứng dụng tại `http://localhost:3000`.

## Đóng Góp

Nhóm hoan nghênh các đóng góp! Vui lòng làm theo các hướng dẫn sau:
- Fork repository.
- Tạo branch mới cho tính năng/sửa lỗi của bạn.
- Gửi pull request với mô tả chi tiết về các thay đổi.