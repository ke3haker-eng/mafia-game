# 🎭 المافيا — مدينة الظلام

> لعبة المافيا الاجتماعية الكاملة — PWA تعمل على الهاتف بدون إنترنت

---

## 🚀 النشر على GitHub Pages (خطوة بخطوة)

### 1. رفع الملفات على GitHub

```bash
git init
git add .
git commit -m "🎭 init: mafia PWA"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/mafia-game.git
git push -u origin main
```

### 2. تفعيل GitHub Pages

1. افتح **Settings** في الـ repository
2. من القائمة الجانبية اختر **Pages**
3. تحت **Source** اختر **GitHub Actions**
4. سيتشغّل الـ workflow تلقائياً عند أي push

### 3. رابط التطبيق

بعد النشر سيكون الرابط:
```
https://YOUR_USERNAME.github.io/REPO_NAME/
```

---

## 📱 تثبيت التطبيق على الجهاز

### Android (Chrome/Edge)
1. افتح الرابط في Chrome
2. انتظر **3-5 ثوانٍ** حتى يظهر بانر "إضافة إلى الشاشة الرئيسية"
3. أو اضغط ⋮ → **تثبيت التطبيق** أو **Add to Home Screen**
4. اضغط **تثبيت** ✅

### iOS (Safari)
1. افتح الرابط في Safari (ليس Chrome)
2. اضغط زر المشاركة 📤
3. اختر **إضافة إلى الشاشة الرئيسية**
4. اضغط **إضافة** ✅

---

## 📂 هيكل الملفات

```
mafia-pwa/
├── index.html          ← اللعبة الكاملة
├── manifest.json       ← إعدادات PWA
├── sw.js               ← Service Worker (offline)
├── 404.html            ← redirect page
├── icons/
│   ├── icon-192x192.png
│   └── icon-512x512.png
└── .github/
    └── workflows/
        └── deploy.yml  ← GitHub Actions
```

---

## ✨ المميزات

- 🎮 **14 دور** مختلف (مافيا، مدنيون، مستقلون)
- 👥 **5 إلى 20 لاعب**
- 🌙 نظام ليل/نهار كامل مع قصص درامية
- 🔊 موسيقى خلفية وأصوات تفاعلية (Web Audio API)
- 📴 **يعمل بدون إنترنت** بعد أول تحميل
- 📲 **PWA** — يُثبَّت كتطبيق على الجهاز
- 🌙 Dark mode فقط (تصميم ليلي احترافي)
- 🇸🇦 واجهة عربية بالكامل (RTL)
