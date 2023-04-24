# Learn PHP Basics

## Nhập môn lập trình PHP

## PHP căn bản 
### Bài 04: Kiểm tra thông tin PHP

```php
phpinfo()
```
---
### Bài 05: Variable
1. Đặt tên biến trong PHP
- Cú pháp: $ten_bien
- Lưu ý: 
  - Tên biến phải bắt đầu bằng chữ cái hoặc gạch dưới
  - Tên biến chứa các chữ cái, chữ số, ký tự gạch dưới
  - PHP không cần khai báo kiểu dữ liệu
  - Nên đặt theo quy tắc camelCase (Ví dụ: $userId)

```php
// Khai báo biến mà không gán giá trị
$myName;
$age;
$mark;
```

2. Gán biến và xuất dữ liệu trong PHP
- Cú pháp: $ten_bien = giá trị 
- Ví dụ: $ten_bien = ‘Unicode’; $ten_bien = 12;
- In dữ liệu:
  - echo <tên biến/tên hàm/chuỗi/số>;
  - Ví dụ: echo $customer_name; echo ‘Unicode’;

```php
$myName = 'Dunlok dev';
echo $myName; // Dunlok dev
```
---

