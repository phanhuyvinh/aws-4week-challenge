# 1. Tên dự án & Mục tiêu
    Personal Task Manager - Ứng dụng web cho phép người dùng thêm, sửa, xóa và đánh dấu hoàn thành các công việc cá nhân.
# 2. Công nghệ sử dụng (Programming language, Framework, Database...).
    Programming language: Python
    Framework: Flask
    Database: MySQL
    Frontend: HTML, CSS, JavaScript
    Deployment: AWS EC2
# 3. Mô tả ngắn gọn cách ứng dụng tương tác với hạ tầng VPC đã thiết kế ở Phần 1.
    Ứng dụng được triển khai trên VPC đã thiết kế. Web Server chạy trong Public Subnet để người dùng có thể truy cập từ Internet. Database MySQL được đặt trong Private Subnet và chỉ cho phép Web Server kết nối đến Database thông qua Security Group. Nhờ đó, Database không được truy cập trực tiếp từ Internet.
