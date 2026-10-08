# موقع ختمة القرآن

## الملفات
- index.html : واجهة المشاركين
- admin.html : لوحة المشرف
- style.css : التصميم
- database.sql : قاعدة Supabase

## الإعداد
1. أنشئ مشروعًا في Supabase.
2. افتح SQL Editor والصق database.sql ثم Run.
3. من Authentication > Users أنشئ حساب المشرف بالبريد وكلمة المرور.
4. في آخر database.sql يوجد أمر لإضافة حسابك إلى جدول admins. استبدل البريد وشغله.
5. من Project Settings > API انسخ:
   - Project URL
   - anon public key
6. ضع القيمتين في index.html و admin.html مكان:
   ضع_رابط_مشروعك_هنا
   ضع_anon_key_هنا

## التشغيل
يمكن فتح الملفات عبر Live Server في VS Code.

## ملاحظة
الموقع يستخدم Supabase لتخزين الحالات بشكل مشترك بين جميع الهواتف.
المشرف يستطيع:
- تأكيد مشارك يدويًا.
- إلغاء التأكيد.
- بدء أسبوع جديد حتى لو لم يكمل الجميع.
- تحديد الحزبين الجديدين.
- إعادة ضبط حالات الأسبوع الحالي.

للنشر العام استخدم Vercel أو Netlify أو GitHub Pages.
