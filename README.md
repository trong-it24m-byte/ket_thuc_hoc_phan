# TechStore (Dự án cửa hàng thiết bị công nghệ)

Một dự án demo cửa hàng thiết bị công nghệ xây trên Django. Bao gồm:
- Quản lý sản phẩm với thông số kỹ thuật (CPU, RAM, Storage, màn hình)
- Giỏ hàng lưu trong session
- Hệ thống chat cơ bản (hỗ trợ user đã đăng nhập và ẩn danh)
- Seed data sẵn để demo (iPhone, MacBook, v.v.)
- Giao diện admin được nâng cấp bằng `jazzmin`

---

## Yêu cầu
- Python 3.10+
- pip
- virtualenv 

Dependencies được liệt kê trong `requirements.txt`.

---

## Quick start (Windows PowerShell)

1. Mở terminal ở thư mục project:

```powershell
cd ket_thuc_hoc_phan-master
```

2. Tạo và kích hoạt virtual environment:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

3. Cài dependencies:

```powershell
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

4. Áp migration và tạo database:

```powershell
python manage.py migrate
```

5. (Tùy chọn) Thêm dữ liệu demo:

```powershell
python seed_data.py
```

6. Chạy server phát triển:

```powershell
python manage.py runserver
```

Mở trình duyệt vào `http://127.0.0.1:8000/` để xem.

---
## Website Demo:
```Website demo
https://ket-thuc-hoc-phan.onrender.com/
``` 

---

