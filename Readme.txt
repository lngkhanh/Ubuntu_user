/var/www : Thư mục mặc định chứa website

/etc/apache2/apache2.conf : File cấu hình Apache2

/etc/apache2/mods-enabled : Thư mục chứa các module của Apache module (các module đang hoạt động

/etc/apache2/sites-enabled : Thư mục chứa các cài đặt định danh cho các website (Virtual Host)

/etc/apache2/conf.d : Các cấu hình mở rộng cho Apache.

Nếu không muốn Apache tự khởi động cùng hệ thống, gõ lệnh sau:

sudo update-rc.d -f apache2 remove

Còn nếu muốn làm ngược lại quá trình trên (khởi động cùng hệ thống) thì sử dụng lệnh:

sudo update-rc.d apache2 defaults
