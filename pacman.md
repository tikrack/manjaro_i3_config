# 📘 Manjaro i3 Basic Commands Cheat Sheet

> مجموعه دستورات کاربردی برای مدیریت سیستم و کار با i3 Window Manager  
> مناسب برای کاربران تازه‌کار و حرفه‌ای در محیط Manjaro i3

---

## ✅ Update Packages

```bash
sudo pacman -Syu
```
> بروزرسانی کامل سیستم (پکیج‌ها)

---

## 🔍 Search Packages

```bash
pamac search <package>
```
> جستجو در پکیج‌های رسمی و AUR

---

## 📦 Install Packages

```bash
pamac install <package>
```
> نصب پکیج از مخازن رسمی یا AUR

---

## ❌ Remove Packages

```bash
pamac remove <package>
```
> حذف کامل یک پکیج و وابستگی‌هایش

---

## 🧼 Clean Cache

```bash
pamac clean
```
> پاکسازی کش پکیج‌های قدیمی برای آزاد کردن فضا

---

## 📁 List Installed Packages

```bash
pacman -Qe
```
> نمایش پکیج‌های نصب‌شده توسط کاربر

---

## 🔄 Reload i3 Config

```bash
i3-msg reload
```
> بارگذاری مجدد تنظیمات i3 بدون ری‌استارت کامل

---

## ♻️ Restart i3

```bash
i3-msg restart
```
> ری‌استارت کامل i3 برای بارگذاری مجدد همه تنظیمات

---

## ⚙️ Edit i3 Config File

```bash
nano ~/.config/i3/config
```
> ویرایش تنظیمات کلیدهای میانبر، استارتاپ، تم و...

---

## 🧠 i3 Keyboard Shortcuts

```text
Mod + Enter        → باز کردن ترمینال
Mod + D            → باز کردن منوی برنامه‌ها (dmenu)
Mod + Shift + Q    → بستن پنجره فعال
Mod + ←↑↓→         → حرکت بین پنجره‌ها
Mod + Shift + ←↑↓→ → جابجایی پنجره‌ها
Mod + H / V        → تقسیم افقی / عمودی
Mod + F            → حالت تمام‌صفحه
Mod + Shift + Space → حالت شناور
Mod + Shift + R    → ری‌استارت i3
Mod + Shift + E    → خروج از i3
```

---

## 🖼 Set Wallpaper

```bash
feh --bg-scale ~/Pictures/wallpaper.jpg
```
> تنظیم تصویر زمینه با ابزار feh

---

## 🔊 Volume Control

```bash
amixer set Master 5%+
amixer set Master 5%-
```
> افزایش یا کاهش صدا

---

## 📡 Network Manager GUI

```bash
nm-connection-editor
```
> مدیریت گرافیکی شبکه‌ها در محیط i3

---

## 🔐 Lock Screen

```bash
i3lock
```
> قفل کردن صفحه با ظاهر ساده

---

> 📌 **نکته:** در i3 بیشتر کارها با کیبورد انجام می‌شود و انعطاف بسیار بالایی دارد. می‌توانید با شخصی‌سازی فایل config، سیستم خود را به ابزار کاری سریع و سبک تبدیل کنید.

---

🛠 توسط [Tikrack](https://github.com/tikrack) با ❤️ در دنیای i3
