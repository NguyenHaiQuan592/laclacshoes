# 👟 LaClac Shoes - E-commerce Website

## 📋 Giới thiệu
LaClac Shoes là website bán giày trực tuyến được xây dựng bằng PHP thuần, cung cấp đầy đủ chức năng cho việc mua bán giày dép online.

## ✨ Tính năng chính

### 🛍️ Khách hàng
- Xem danh sách sản phẩm với phân trang
- Tìm kiếm và lọc sản phẩm theo danh mục
- Xem chi tiết sản phẩm (hình ảnh, màu sắc, size)
- Thêm sản phẩm vào giỏ hàng
- Thanh toán và đặt hàng
- Đăng ký/Đăng nhập tài khoản
- Quản lý thông tin cá nhân
- Đánh giá sản phẩm

### ⚙️ Admin
- Quản lý danh mục sản phẩm
- Quản lý sản phẩm (CRUD)
- Quản lý kho hàng (nhập/xuất)
- Xử lý đơn hàng
- Quản lý khách hàng
- Quản lý nhân viên với phân quyền
- Báo cáo doanh thu
- Quản lý khuyến mãi

## 🛠️ Công nghệ sử dụng

### Backend
- **PHP** thuần (không framework)
- **MySQL** database
- **PHPMailer** cho email notifications

### Frontend
- **HTML5, CSS3, JavaScript**
- **Bootstrap 5** responsive framework
- **MDB** (Material Design Bootstrap)
- **jQuery** + plugins (Flexslider, Owl Carousel)
- **Font Awesome** icons

## 📦 Cài đặt

### Yêu cầu hệ thống
- PHP 7.4+
- MySQL 5.7+
- Web Server (Apache/Nginx)

### Các bước cài đặt

1. **Clone repository**
   ```bash
   git clone https://github.com/NguyenHaiQuan592/laclacshoes.git
   ```

2. **Import database**
   - Tạo database tên `laclacshoes`
   - Import file SQL vào database

3. **Cấu hình kết nối database**
   - Mở file `model/database.php`
   - Cập nhật thông tin kết nối MySQL

4. **Chạy website**
   - Đặt project vào thư mục web server
   - Truy cập: `http://localhost/laclacshoes`

## 🎯 Demo

### Frontend (Khách hàng)
- **Trang chủ**: `http://localhost/laclacshoes`
- **Đăng nhập**: `http://localhost/laclacshoes/view/login.php`

### Backend (Admin)
- **Admin panel**: `http://localhost/laclacshoes/admin`

## 📁 Cấu trúc thư mục

```
laclacshoes/
├── admin/              # Admin panel
├── controller/         # Controllers
├── model/             # Models & Database
├── view/              # Views (Frontend)
├── webroot/           # Assets (CSS, JS, Images)
│   ├── css/
│   ├── js/
│   ├── image/
│   └── PHPMailer/
└── index.php          # Entry point
```

## 🤝 Đóng góp
Mọi đóng góp đều được chào đón! Hãy tạo pull request hoặc mở issue để thảo luận.

## 📞 Liên hệ
- **Email**: quannguyen050992@gmail.com
- **GitHub**: [NguyenHaiQuan592](https://github.com/NguyenHaiQuan592)

## 📄 License
Dự án này được phát hành dưới [MIT License](LICENSE).

---
⭐ **Nếu dự án hữu ích, hãy cho một star để ủng hộ!** ⭐