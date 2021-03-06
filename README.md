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
![start_project](https://user-images.githubusercontent.com/103992475/164141175-ccfbf502-e4cd-4532-b64a-b138f59f3fa8.png)

Cấu trúc thư mục của project sau khi tạo:

![structure](https://user-images.githubusercontent.com/103992475/164141299-91ca209f-cf1d-43c5-affd-7dbcc6846a97.png)

Trong đó có 3 file đáng lưu ý là `items.py`, `pipelines.py` và `settings.py`. Ngoài ra còn có thư mục spiders nhưng không chứa gì ngoài file `__init__.py`. Trong phần này ta sẽ chủ yếu làm việc với `items.py` và những gì trong thư mục spiders.
