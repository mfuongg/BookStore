![MyProject Banner](https://github.com/ca-xao-xa-ot/BookStore/blob/main/public/assets/images/myproject.jpeg?raw=true)

<h1>About us</h1>
<ul>
    <a href = '' ><li>Nguyễn Thị Thu Giang - 23010871</li></a>
    <a href = '' ><li>Ngô Thị Minh Phương - 23012156</li></a>
</ul>
<p>We're all from PHENIKAA UNIVERSITY</p>

# Shop-Ban-Sach-Laravel

# Thông tin về project:

    -Là một trang web bán sách trực tuyến được xây dựng bằng Laravel.
    -Người dùng có thể đăng ký, đăng nhập, xem danh sách sách, tìm kiếm, thêm vào giỏ hàng và đặt hàng.
    -Quản trị viên (Admin) có thể quản lý sách, danh mục, người dùng và đơn hàng.
    -Hệthống sử dụng các models chính như: User, Book, Cart, Order, Review, Category.
    -Hướng tới thiết kế MVC rõ ràng, dễ mở rộng trong tương lai.

# cách cài đặt web sau khi tải về:

1. giải nén.
2. đảm bảo Laravel project thật sự nằm bên trong thư mục con cần chạy.
3. cài đặt thư viện laravel = composer : composer install.
4. cài xong thì chạy : php artisan serve.
5. Tạo .env:
   Bước 1: cp .env.example .env
   Bước 2: DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_USERNAME=root
   DB_PASSWORD=
   Bước 3: Tạo key cho Laravel (nếu chưa có) php artisan key:generate
   Bước 4: php artisan serve
   (đảm bảo kết nối mysql ( Xampp)- shop_ban_sach)
