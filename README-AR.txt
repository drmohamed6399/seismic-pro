طريقة تحويل Seismic Pro إلى تطبيق (PWA)

1) ارفع محتويات هذا المجلد كما هي إلى استضافة HTTPS مجانية:
   - Netlify Drop: اسحب المجلد إلى app.netlify.com/drop
   - أو GitHub Pages / Cloudflare Pages
2) افتح الرابط على الهاتف:
   - Android (Chrome): القائمة ⋮ ثم "تثبيت التطبيق"
   - iPhone (Safari): مشاركة ثم "إضافة إلى الشاشة الرئيسية"
   - الكمبيوتر (Chrome/Edge): أيقونة التثبيت في شريط العنوان
3) بعد أول فتح بالإنترنت يعمل التطبيق بدون إنترنت.

للحصول على ملف APK:
   افتح pwabuilder.com، الصق رابط موقعك، واختر Android ثم Download.

عند تحديث التطبيق مستقبلا: غيّر رقم CACHE في sw.js (مثلا seismic-v3-2).
