# MMD Subscription Template

#تلگرام : https://t.me/bang_code
یک قالب ساده، سریع و مدرن برای نمایش اطلاعات اشتراک و کانفیگ‌ها در **Rebecca**.

طراحی شده و بازطراحی‌شده توسط **@GGCODER_IR**

---

## ✨ قابلیت‌ها

- طراحی مدرن و سبک
- پشتیبانی از زبان فارسی و انگلیسی
- حالت تاریک و روشن
- نمایش حجم مصرف‌شده
- نمایش حجم باقی‌مانده
- نمایش تاریخ انقضا
- نمایش وضعیت اشتراک
- جستجوی کانفیگ
- فیلتر کانفیگ بر اساس پروتکل
- کپی کانفیگ تکی
- کپی کانفیگ‌های انتخاب‌شده
- کپی همه کانفیگ‌ها
- خروجی TXT
- خروجی JSON
- کپی لینک اشتراک
- اشتراک‌گذاری لینک اشتراک
- پشتیبانی از فایل‌های VPN
- OpenVPN
- WireGuard
- L2TP
- PPTP
- بدون نیاز به npm
- بدون نیاز به build
- بدون CDN خارجی
- کاملاً تک‌فایلی

---

# 🚀 نصب سریع

برای نصب قالب، دستور زیر را اجرا کنید:

```bash
wget -O /var/lib/rebecca/templates/subscription/index.html \
https://github.com/ggcoder021/rebeca_ggcoder_sub/releases/latest/download/index.html
```



### مثال

```bash
wget -O /var/lib/rebecca/templates/subscription/index.html \
https://github.com/ggcoder021/rebeca_ggcoder_sub/releases/latest/download/index.html
```

بعد از اجرای دستور، قالب به‌صورت خودکار در مسیر زیر نصب می‌شود:

```text
/var/lib/rebecca/templates/subscription/index.html
```

---

# 🛠 نصب دستی

اگر نمی‌خواهید از `wget` استفاده کنید:

1. فایل `index.html` را دانلود کنید.
2. وارد سرور شوید.
3. فایل را در مسیر زیر قرار دهید:

```text
/var/lib/rebecca/templates/subscription/index.html
```

اگر فایل قبلی وجود داشت، آن را جایگزین کنید.

---

# 🔄 آپدیت قالب

برای آپدیت به آخرین نسخه فقط دوباره دستور زیر را اجرا کنید:

```bash
wget -O /var/lib/rebecca/templates/subscription/index.html \
https://github.com/USERNAME/REPOSITORY/releases/latest/download/index.html
```

---

# 🎨 تغییر ظاهر

برای تغییر رنگ‌ها، فایل `index.html` را باز کنید.

در قسمت `:root` این بخش را پیدا کنید:

```css
:root{
  --accent:#7c8cff;
  --accent2:#50e3c2;
}
```

### تغییر رنگ اصلی

```css
--accent:#7c8cff;
```

### تغییر رنگ دوم

```css
--accent2:#50e3c2;
```

---

# 🏷 تغییر نام Aurora

داخل فایل `index.html` عبارت زیر را پیدا کنید:

```text
Aurora
```

و آن را با نام دلخواه خودتان جایگزین کنید.

---

# 👤 تغییر سازنده

برای تغییر نام سازنده، عبارت زیر را جستجو کنید:

```text
@GGCODER_IR
```

---

# 📁 ساختار پروژه

```text
Aurora/
├── index.html
├── README.md
├── LICENSE
└── .gitignore
```

---

# ⚠️ نکته مهم

این قالب برای استفاده به‌عنوان **Subscription Template** طراحی شده است.

برای عملکرد صحیح، بخش زیر را حذف نکنید:

```html
<div id="aurora-data">
```

متغیرهای Template مربوط به اطلاعات کاربر و اشتراک باید دست‌نخورده باقی بمانند.

---

# 👨‍💻 Credits

ساخته و بازطراحی‌شده توسط:

**@GGCODER_IR**

---

# 📄 License

این پروژه تحت لایسنس MIT منتشر شده است.

---

> **نکته:** برای استفاده از مسیر `releases/latest/download/index.html` باید ابتدا یک Release با نسخه‌ای مثل `v1.0.0` بسازید و فایل `index.html` را به‌عنوان Release Asset آپلود کنید.
