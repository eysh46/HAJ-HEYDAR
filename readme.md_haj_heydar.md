# 🛡️ دژ ارتباطی شاهنشاهی HAJ_HEYDAR

[![Vercel Deployment](https://img.shields.io/badge/Deploy-Vercel-black?style=for-the-badge&logo=vercel)](https://vercel.com)
[![License](https://img.shields.io/badge/License-MIT-gold?style=for-the-badge)](LICENSE)
[![Xray-Core](https://img.shields.io/badge/Core-Xray--1.8.8-00f0ff?style=for-the-badge)](https://github.com/XTLS/Xray-core)
[![Release](https://img.shields.io/badge/Release-v4.9.2-10b981?style=for-the-badge)](https://github.com)

> **سریع‌ترین و نفوذناپذیرترین کلاینت ضد فیلترینگ با تم زرین شاهنشاهی هخامنشی، هسته شتاب‌یافته Xray، رمزنگاری کوانتوم‌مقاوم و مسیریابی چندمسیره BGP.**

---

## 🏛️ ویژگی‌های کلیدی پروژه

- ⚡ **هسته بهینه‌سازی‌شده Xray:** پشتیبانی کامل از پروتکل‌های نسل جدید `VLESS`, `Reality`, `gRPC`, `Hysteria-2`, `TUIC v5` و `Shadowsocks 2022`.
- 👑 **هویت بصری شاهنشاهی هخامنشی (Imperial Basalt & Gold):** رابط کاربری با الهام از تالار آپادانا و تخت جمشید با سنگ بازالت سیاه و خطوط طلای ناب.
- 💻 **سازگاری چندپلتفرمه:**
  - کلاینت اندروید (فایل نصبی مستقیم APK + بارکد اسکن دوربین)
  - کلاینت ویندوز (Setup.exe اختصاصی + نسخه پرتابل Portable.zip با درایور در سطح هسته Wintun L3)
  - اشتراک ۱-کلیکه برای iOS / macOS (قابل استفاده در Shadowrocket و Sing-box)
  - اسکریپت تک‌خطی برای سرورهای لینوکس و مودم‌های OpenWrt
- 🔒 **منشور امنیت و صیانت از داده (Zero Logs):** تضمین ۱۰۰٪ عدم ذخیره‌سازی آی‌پی و گزارش ترافیک کاربران.
- 🎛️ **پنل فرماندهی روت سازنده (Master Hub):** مدیریت متمرکز نسخه‌ها، تغییر آنی لینک‌های دانلود و کنترل شماره کارت/ولیت‌های حمایت مالی.

---

## 📁 ساختار پوشه‌ها و فایل‌های مخزن

```text
haj-heydar-tunnel/
│
├── index.html              # لندینگ‌پیج اصلی و مرکز معرفی و دانلود کلاینت‌ها (صفحه دسکتاپ/ریشه)
├── download.html           # مرکز دانلود اختصاصی موبایل و ویندوز با بارکد QR و چنج‌لاگ
├── servers.html            # لیست زنده درگاه‌ها و سرورها (فرانکفورت، دبی، استانبول، هلسینکی)
├── master-hub.html         # پنل فرماندهی و مدیریت روت سازنده (کنترل نسخه‌ها و کارت بانکی)
│
├── vercel.json             # تنظیمات استقرار Vercel (مسیریابی تمیز، هدرهای امنیتی و کش)
├── README.md               # مستندات رسمی مخزن و راهنمای نصب و راه‌اندازی
│
└── assets/                 # فایل‌های استاتیک و آیکون‌ها
    ├── icons/              # آیکون‌ها و نمادهای زرین هخامنشی
    └── logos/              # نشان رسمی شاهنشاهی HAJ_HEYDAR
```

---

## 🚀 راهنمای سریع راه‌اندازی و دیپلوی

### روش اول: استقرار ۱-کلیکه روی Vercel (پیشنهادی)

1. مخزن را فورک (Fork) کنید یا در اکانت گیت‌هاب خود ایجاد نمایید.
2. وارد پنل [Vercel](https://vercel.com) شوید.
3. روی **Add New...** > **Project** کلیک کرده و مخزن `haj-heydar-tunnel` را Import کنید.
4. تنظیمات زیر به شکل خودکار از `vercel.json` اعمال خواهد شد:
   - **Framework Preset:** `Other`
   - **Root Directory:** `./`
5. دکمه **Deploy** را بزنید. دامنه اختصاصی HTTPS شما در چند ثانیه آماده استفاده عمومی است!

---

### روش دوم: اجرای لوکال با گیت و سرور محلی

```bash
# ۱. کلون کردن مخزن
git clone https://github.com/USERNAME/haj-heydar-tunnel.git

# ۲. ورود به دایرکتوری
cd haj-heydar-tunnel

# ۳. اجرای سرور ساده روی سیستم (مثلاً با پایتون)
python3 -m http.server 3000

# ۴. باز کردن در مرورگر
# http://localhost:3000
```

---

## 📦 قرار دادن فایل‌های نصبی در بخش Releases گیت‌هاب

برای اینکه لینک‌های دانلود APK و Setup.exe به صورت دائمی، پایدار و با سرعت حداکثری کار کنند:

1. وارد تب **Releases** مخزن گیت‌هاب شوید.
2. بر روی **Draft a new release** کلیک کنید.
3. یک برچسب نسخه مانند `v4.9.2` تعیین کنید.
4. فایل‌های باینری زیر را آپلود نمایید:
   - `HAJ_HEYDAR_v4.9.2.apk`
   - `HAJ_HEYDAR_Setup_x64.exe`
   - `HAJ_HEYDAR_Portable_x64.zip`
5. دکمه **Publish release** را بزنید و لینک مستقیم فایل‌های آپلود شده را در `index.html` و پنل `master-hub.html` قرار دهید.

---

## 🛡️ امنیت و لایسنس

این پروژه تحت لایسنس [MIT License](LICENSE) منتشر شده است. تمامی کدها با استاندارد W3C معتبر بوده و برای استقرار پایدار در شبکه توزیع محتوا (CDN) بهینه‌سازی شده‌اند.
