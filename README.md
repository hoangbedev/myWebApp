# myWebApp
# PHP Programming
## Chương 1: Giới thiệu về PHP và Laravel
### Khoá học Coursera – Khóa 1 – Module 1

### 1.1 Giới thiệu về PHP

PHP (viết tắt của Hypertext Preprocessor) là một ngôn ngữ lập trình kịch bản mã nguồn mở, chuyên dùng để phát triển các ứng dụng web động.

PHP có thể được nhúng trực tiếp vào các tệp HTML.

Được tạo bởi Rasmus Lerdorf vào năm 1994.

Hiện nay là một trong những ngôn ngữ phổ biến nhất để xây dựng trang web.

### 1.2 Cú pháp cơ bản trong PHP

Mã PHP được đặt giữa thẻ <?php ... ?>.

Mỗi câu lệnh kết thúc bằng dấu chấm phẩy ;.

Biến

Bắt đầu bằng ký tự $.

Ví dụ: $ten = "PHP";

Ghi chú (Comments)

Ghi chú một dòng: //

Ghi chú nhiều dòng:

/* Ghi chú
   nhiều dòng */


Phân biệt chữ hoa/thường

Tên biến: phân biệt chữ hoa/thường ($Name khác $name).

Từ khóa, hàm, class: không phân biệt chữ hoa/thường.

### 1.3 Cấu trúc điều khiển

Câu lệnh điều kiện

if, else, elseif: thực hiện các nhánh mã dựa trên điều kiện.

switch: chọn một trong nhiều trường hợp để thực thi.

Ví dụ:

$diem = 8;
if ($diem >= 9) {
    echo "Xuất sắc!";
} elseif ($diem >= 7) {
    echo "Giỏi!";
} else {
    echo "Cố gắng hơn nhé!";
}


Vòng lặp

for: lặp với số lần xác định.

while: lặp khi điều kiện còn đúng.

do...while: thực hiện ít nhất một lần trước khi kiểm tra điều kiện.

foreach: lặp qua từng phần tử trong mảng.

Ví dụ:

for ($i = 1; $i <= 5; $i++) {
    echo "Dòng thứ $i<br>";
}

### 1.4 Hàm trong PHP

Dùng để đóng gói các khối mã lặp lại, dễ bảo trì và tái sử dụng.

Cú pháp:

function tenHam($thamSo) {
    return $giaTri;
}


Gọi hàm:

tenHam("giá trị");

### 1.5 Vai trò của PHP trong phát triển ứng dụng web

PHP hoạt động như một ngôn ngữ lập trình phía máy chủ (server-side), xử lý logic và dữ liệu trước khi gửi kết quả ra trình duyệt người dùng dưới dạng HTML.

Các vai trò chính của PHP:

Tạo nội dung động trên trang web.

Xử lý biểu mẫu HTML (form): đăng ký, đăng nhập,...

Kết nối và thao tác với cơ sở dữ liệu (MySQL, PostgreSQL,...).

Quản lý phiên (session): lưu thông tin người dùng.

Tạo API để giao tiếp với các hệ thống khác.

PHP được sử dụng bởi nhiều nền tảng lớn như WordPress, Facebook, Wikipedia,...

### 1.6 Laravel – Giới thiệu sơ lược

Laravel là một framework PHP hiện đại, được thiết kế để giúp lập trình viên phát triển ứng dụng web nhanh chóng và hiệu quả.

Áp dụng mô hình MVC (Model - View - Controller).

Cung cấp sẵn các chức năng như: routing, session, authentication, validation, Blade template, Artisan CLI,...

Tối ưu cho bảo trì mã nguồn và mở rộng hệ thống.
