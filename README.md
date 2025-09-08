# Django Charity Project

یک پروژه‌ی جنگو برای مدیریت حساب کاربری، خیریه‌ها و بخش "درباره ما".

## 🚀 ویژگی‌ها
- احراز هویت کاربران (Custom User Model)
- API با استفاده از Django REST Framework
- مدیریت خیریه‌ها
- صفحات استاتیک (About Us)
- ساختار ماژولار (اپ‌های accounts, charities, about_us)

## 📦 نصب و اجرا

### 1. کلون کردن ریپوزیتوری
```bash
git clone https://github.com/your-username/charity-project.git
cd charity-project/django_project
```

### 2. ایجاد محیط مجازی
```bash
python -m venv venv
source venv/bin/activate   # در لینوکس/مک
venv\Scripts\activate      # در ویندوز
```

### 3. نصب وابستگی‌ها
```bash
pip install -r requirements.txt
```

### 4. تنظیم متغیرهای محیطی
یک فایل `.env` ایجاد کنید و مقادیر زیر را وارد کنید (می‌توانید از `.env.example` استفاده کنید):
```env
DJANGO_SECRET_KEY=your-secret-key
DJANGO_DEBUG=True
DJANGO_ALLOWED_HOSTS=localhost,127.0.0.1
```

### 5. اجرای مهاجرت‌ها
```bash
python manage.py migrate
```

### 6. اجرای سرور توسعه
```bash
python manage.py runserver
```

## 🛠 ساختار پروژه
```
django_project/
│── accounts/       # مدیریت کاربران
│── charities/      # مدیریت خیریه‌ها
│── about_us/       # صفحه درباره ما
│── charity/        # تنظیمات اصلی پروژه
│── manage.py
│── requirements.txt
│── .gitignore
│── .env.example
│── README.md
```

## 🧪 تست
```bash
python manage.py test
```

## 📄 لایسنس
این پروژه تحت مجوز MIT منتشر شده است.
# django-charity-project

