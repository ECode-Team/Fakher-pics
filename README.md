# Fakher-pics

<div align="right" dir="rtl">

<div align="center">

  <img src="https://readme-typing-svg.herokuapp.com?font=Vazir&size=30&pause=1000&color=7D4F39&center=true&vCenter=true&width=500&lines=سامانه+جامع+فروشگاه+مبلمان+فاخر;تجربه+خرید+مدرن+با+Next.js;مدیریت+هوشمند+با+Django" alt="Typing SVG" />

  <br />

  <p>
    <img src="https://img.shields.io/badge/Front--End-Next.js%20%7C%20Tailwind-blue?style=for-the-badge" />
    <img src="https://img.shields.io/badge/Back--End-Django%20%7C%20Python-green?style=for-the-badge" />
    <img src="https://img.shields.io/badge/Database-PostgreSQL-blue?style=for-the-badge" />
    <img src="https://img.shields.io/badge/DevOps-Redis%20%7C%20Nginx-red?style=for-the-badge" />
  </p>

  <p align="center">
    <img src="./home-page.png" alt="صفحه اصلی" width="32%" style="border-radius: 10px; border: 1px solid #eee;" />
    <img src="./product-page.png" alt="صفحه محصول" width="32%" style="border-radius: 10px; border: 1px solid #eee;" />
    <img src="./admin-panel.png" alt="پنل مدیریت" width="32%" style="border-radius: 10px; border: 1px solid #eee;" />
  </p>

</div>

---

## 💎 درباره پروژه "مبلمان فاخر "

این پروژه یک پلتفرم تجارت الکترونیک (E-commerce) کامل برای صنایع چوب و مبلمان است. سیستم شامل یک **فرانت‌اِند** فوق‌سریع برای کاربران، **پنل مدیریت اختصاصی** برای کنترل محصولات و محتوا، و زیرساخت **دِواپس** برای پایداری بالا می‌باشد.

### ✨ قابلیت‌های اصلی

* **🛒 فروشگاه پیشرفته:** قابلیت فیلتر محصولات، نمایش جزئیات فنی و محصولات مرتبط.
* **🛠️ پنل مدیریت جامع:** مدیریت صفحات سایت، آمار فروش، تنظیمات فوتر و موجودی انبار.
* **📱 کاملاً ریسپانسیو:** تجربه کاربری یکسان در موبایل، تبلت و دسکتاپ.
* **🚀 سئو و کارایی:** استفاده از SSR و بومی‌سازی کامل برای موتورهای جستجو.

---

## 🛠️ پشته تکنولوژی (Tech Stack)

<div align="center">

| بخش | تکنولوژی‌های استفاده شده |
| :--- | :--- |
| **Frontend** | `Next.js 14`, `React`, `Tailwind CSS`, `TypeScript` |
| **Backend** | `Django`, `Django Rest Framework (DRF)` |
| **Database** | `PostgreSQL`, `Redis (Caching)` |
| **DevOps** | `Nginx`, `Prometheus`, `Grafana`, `Docker` |

</div>

---

## 🚀 راهنمای نصب و اجرا

برای راه‌اندازی پروژه در محیط محلی، دستورات زیر را اجرا کنید:

```bash
# ۱. کلون کردن پروژه
git clone [https://github.com/your_username/choub-fakher.git](https://github.com/your_username/choub-fakher.git)

# ۲. نصب وابستگی‌های فرانت‌اِند و اجرا
cd frontend
npm install
npm run dev

# ۳. راه‌اندازی بک‌اِند (Django)
cd ../backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver