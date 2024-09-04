# Student Management

## Giới thiệu

"Student Management" là một ứng dụng quản lý sinh viên được phát triển bằng Java Swing cho giao diện người dùng (UI) và Node.js với Express.js cho backend. Ứng dụng cho phép quản lý thông tin giáo viên, sinh viên và các lớp học một cách hiệu quả.

## Các tính năng chính

- Quản lý sinh viên: Thêm, sửa, xóa và xem thông tin sinh viên.
- Quản lý giáo viên: Thêm, sửa, xóa và xem thông tin giáo viên.
- Quản lý lớp học: Thêm, sửa, xóa và xem thông tin lớp học.
- Xác thực và phân quyền: Hệ thống đăng nhập với vai trò quản trị viên.
- ...

## Cấu trúc dự án

### 1. Giao diện người dùng (Frontend)

- Ngôn ngữ: Java
- Thư viện: Java Swing
- Thư mục chứa thư viện: `lib/`

### 2. Backend

- Ngôn ngữ: JavaScript (Node.js)
- Framework: Express.js
- Kho lưu trữ backend: [Student Management Server](https://github.com/NQTrung08/Student-Management-Server)

## Hướng dẫn cài đặt

### 1. Cài đặt Backend

#### Yêu cầu:
- Node.js v14 trở lên
- MongoDB (hoặc một cơ sở dữ liệu khác mà bạn chọn)

#### Các bước cài đặt:

1. Clone repository backend từ GitHub:
   ```bassh
   git clone https://github.com/NQTrung08/Student-Management-Server.git
   cd Student-Management-Server
   ```

2. Cài đặt các gói phụ thuộc:
   ```bash
   npm install
   ```

3. Tạo file `.env` dựa trên mẫu `.env.example` và cấu hình các biến môi trường cần thiết.

4. Khởi động server:
   ```bash
   npm start
   ```

   Backend sẽ chạy trên `http://localhost:8080` (có thể thay đổi trong `.env`).

### 2. Cài đặt Frontend

#### Yêu cầu:
- JDK 8 trở lên
- Apache Maven

#### Các bước cài đặt:

1. Clone repository này:
   ```bash
   git clone <https://github.com/tiennehihi/JavaSwing_StudentManagement.git>
   cd Student-Management
   ```

2. Thêm các thư viện cần thiết vào thư mục `lib/` hoặc cấu hình Maven để quản lý phụ thuộc.

3. Cấu hình kết nối với backend bằng cách chỉnh sửa các đường dẫn API trong mã Java.

4. Chạy ứng dụng Java Swing:
   - Nếu bạn đang sử dụng IDE như IntelliJ IDEA hoặc Eclipse, hãy mở dự án và chạy lớp chính (`Application.java`).
   - Hoặc chạy từ dòng lệnh:
     ```bash
     javac -cp lib/*:. main/java/com/TLU/studentmanagement/Application.java
     java -cp lib/*:. main/java/com/TLU/studentmanagement/Application
     ```

## Sử dụng

- Mở ứng dụng và đăng nhập bằng thông tin đăng nhập quản trị viên.
- Sử dụng các chức năng trong menu để quản lý sinh viên, giáo viên và lớp học.
- Tất cả các thao tác CRUD sẽ được gửi đến backend để lưu trữ và xử lý.

## Đóng góp

Chúng tôi hoan nghênh mọi sự đóng góp từ cộng đồng. Hãy tạo pull request hoặc mở issue nếu bạn tìm thấy lỗi hoặc có ý tưởng cải tiến.

## Giấy phép

Dự án này được cấp phép dưới giấy phép MIT. Xem file `LICENSE` để biết thêm chi tiết.

## Liên hệ

Nếu bạn có bất kỳ câu hỏi hoặc thắc mắc nào, hãy liên hệ với chúng tôi qua email: [vu_duc_tien@outlook.com.vn].
