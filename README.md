# Scrapy

### Mục lục 
[1. Giới thiệu](#introduction)
  - [1.1. Cài đặt](#install)
  - [1.2. Kiểm tra version](#version)

[2. Bắt đầu project bằng scrapy](#getting_started_project)
  - [2.1. Tạo một project](#create_a_project)
<a name="introduction"></a>
##  1. Giới thiệu 
Scrapy là một web framework rất mạnh mẽ trong việc trích xuất dữ liệu.

* **Ưu điểm:**

  - Hiệu suất tuyệt vời bởi cơ chết bất đồng bộ.
  - Sử dụng rất ít RAM và CPU.
  - Tài liệu đầy đủ

* **Nhược điểm:**
  
  - Hơi phức tạp cho người mới bắt đầu.
  - Không lấy được nội dung trang được render bằng js (kiểm tra: Ctrl + u xem nội dung HTML có như hiển thị không).

<a name="install"></a>
### 1.1. Cài đặt 
Để có thể cài đặt và sử dụng Scrapy thì ta cần có Python 3 trong máy. Để cài đặt Scrapy thì ta dùng trình pip:
```
pip install scrapy
```

<a name="version"></a>
### 1.2. Kiểm tra version 
Kiểm tra version vừa cài đặt:
```
scrapy version
```
![version](https://user-images.githubusercontent.com/103992475/164134659-a620b3e4-3b13-4513-b156-56c0bdba5c81.png)

<a name="getting_started_project"></a>
## 2. Bắt đầu project bằng scrapy

<a name="create_a_project"></a>
### 2.1. Tạo một project
Trước khi bắt đầu crawl dữ liệu, ta cần tạo một project theo câu lệnh sau:
```
scrapy startproject project_name
```
![start_project](https://user-images.githubusercontent.com/103992475/164135891-402f950b-1232-433f-9931-3c9b6cea4b30.png)

