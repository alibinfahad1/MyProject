# الضامن | Aldhamn

موقع عرض (Pitch Page) لمشروع الضامن — طبقة الثقة لما بعد الشراء.

## الملفات

- `index.html` — الصفحة الرئيسية للموقع.
- `admin.html` — لوحة تحرير المحتوى (تقرأ/تكتب `content.json` عبر GitHub API).
- `content.json` — كل نصوص الموقع (عربي/إنجليزي)، يقرأها `index.html` مباشرة.
- `logo.png` — شعار الموقع، يُستخدم في الصفحة الرئيسية ولوحة التحكم (favicon).
- `assets/styles.css`, `assets/app.js` — تنسيقات وسكربت الصفحة الرئيسية.
- `assets/admin.css`, `assets/admin.js` — تنسيقات وسكربت لوحة التحكم.

## تعديل المحتوى

افتح `admin.html`، عدّل النصوص، ثم اضغط «حفظ ونشر» بعد إدخال GitHub Fine-grained Token
بصلاحية `Contents: Read and write` على هذا المستودع فقط.

## التشغيل محلياً

الموقع ثابت (static)، يكفي فتح `index.html` عبر أي سيرفر ملفات محلي، مثال:

```bash
ruby -run -e httpd . -p 8000
```
