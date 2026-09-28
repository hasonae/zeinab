# Zeinab ALI — Marketing Portfolio

ملف واحد ثابت بدون أي خطوة بناء (no build step): `index.html` + أصول الصورة `zeinab.jpg` / `zeinab-icon.png`.

## Live site
https://hasonae.github.io/zeinab/

## معاينة محلية / Local preview
افتح `index.html` مباشرة في المتصفح، أو شغّل سيرفرًا محليًا:

```bash
python -m http.server 8080
```

## تعديل المحتوى / Editing content
- كل شيء داخل `index.html`: الـ markup والـ CSS والـ JavaScript (بدون أي حزم).
- اضغط زر **Edit** في أعلى الصفحة لفتح لوحة التحكم. كلمة المرور الافتراضية `12344321` — غيّرها من نفس اللوحة (تُخزَّن مشفّرة في المتصفح عبر `localStorage`).
- يمكن تعديل: النصوص التعريفية، **الصورة الشخصية** (رابط أو رفع من الجهاز)، المشاريع (العنوان/الوصف/الصورة)، ولون التمييز (Orange/Green/Pink).
- زر **AR/EN** يبدّل لغة الصفحة كاملة (القاموس `arabicText` داخل السكربت).

## النشر / Deployment
GitHub Pages من فرع `main` ومن جذر المستودع (Root).

## ملاحظات / Notes
- التغييرات التي تُجرى من لوحة التحكم تُحفظ في المتصفح فقط (`localStorage`) ولا تُرفع للمستودع. لجعلها دائمة: عدّل `index.html` ثم أضف commit جديد.
- الملف `zeinab.jpg` هو الصورة الشخصية الافتراضية (1000×1252 بنسبة 4:5، JPEG بجودة 82 ≈ 161 KB بدل 2 MB الأصلية)، و`zeinab-icon.png` (96×96) هو الـ favicon و`zeinab-icon-180.png` (180×180) هو أيقونة شاشة الهاتف.
- الملف الأصلي `zeinab.png` (1121×1403) محفوظ في المستودع للمرجعية فقط، ولا يُحمّله الموقع.
