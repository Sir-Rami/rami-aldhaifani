# 🚀 تعليمات نشر الموقع على GitHub Pages

## الخطوات البسيطة:

### 1️⃣ إنشاء مستودع جديد على GitHub
- اذهب إلى [GitHub.com](https://github.com)
- اضغط على "New repository" (مستودع جديد)
- اسم المستودع: `rami-al-dhaifani-portfolio`
- اجعله عام (Public)
- **لا تضع علامة** على "Add a README file"
- اضغط "Create repository"

### 2️⃣ رفع الملفات إلى GitHub

افتح Command Prompt أو PowerShell واكتب:

```bash
# الانتقال إلى مجلد المشروع
cd d:/My-profile

# تهيئة Git
git init

# إضافة جميع الملفات
git add .

# حفظ التغييرات
git commit -m "Initial commit: Professional portfolio website"

# ربط المشروع بـ GitHub (استبدل YOUR-USERNAME باسم المستخدم الخاص بك)
git remote add origin https://github.com/YOUR-USERNAME/rami-al-dhaifani-portfolio.git

# رفع الملفات
git branch -M main
git push -u origin main
```

### 3️⃣ تفعيل GitHub Pages
- اذهب إلى مستودعك على GitHub
- اضغط على "Settings" (الإعدادات)
- انزل إلى قسم "Pages"
- في "Source" اختر "Deploy from a branch"
- اختر "main" branch و "/ (root)" folder
- اضغط "Save"

### 🎉 النتيجة
موقعك سيكون متاحاً على:
`https://YOUR-USERNAME.github.io/rami-al-dhaifani-portfolio`

## 📋 الملفات الجاهزة للرفع:
✅ جميع ملفات الموقع (12 ملف)
✅ تكوين GitHub Actions للنشر التلقائي
✅ ملف .gitignore محسّن
✅ README شامل بالإنجليزية
✅ تعليمات النشر

## 🔗 الروابط المتاحة:
- **Netlify**: https://rami-al-dhaifani.windsurf.build (متاح الآن)
- **GitHub Pages**: سيكون متاحاً بعد اتباع الخطوات أعلاه

---
**ملاحظة**: استبدل `YOUR-USERNAME` باسم المستخدم الخاص بك على GitHub
