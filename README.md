# Hệ thống quản lý quán cà phê ☕️
Hệ thống này được xây dựng bằng PHP để hỗ trợ quản lý các hoạt động kinh doanh của quán cà phê, bao gồm quản lý menu, nhân viên, khách hàng, hóa đơn, và thống kê doanh thu.
### Mô tả dự án
Hệ thống cung cấp các tính năng chính như:
- Quản lý thực đơn (thêm, sửa, xóa món).
- Quản lý nhân viên và phân quyền.
- Quản lý khách hàng và lịch sử giao dịch.
- Lập hóa đơn theo thời gian thực.
- Báo cáo và thống kê doanh thu.
### Tính năng
- Dành cho quản trị viên:
    Quản lý món ăn/thức uống trong menu.
    Quản lý danh sách nhân viên.
    Xem thống kê doanh thu theo ngày, tháng, năm.
- Dành cho nhân viên:
    Tạo và xử lý hóa đơn cho khách hàng.
    Tìm kiếm món và tra cứu thông tin khách hàng.
### Hướng dẫn cài đặt
- Cài đặt Clone repo:
    git clone https://github.com/vuhuyen1523/Coffee-Management.git
    cd Coffee-Management
- Cài đặt XAMPP và đặt thư mục dự án vào thư mục htdocs
- Khôi phục cơ sở dữ liệu:
    Mở phpMyAdmin tại http://localhost/phpmyadmin.
    Tạo database CoffeeShopDB.
    Import file database/duanone.sql.
- Truy cập ứng dụng qua trình duyệt tại http://localhost/Coffee-Management.
