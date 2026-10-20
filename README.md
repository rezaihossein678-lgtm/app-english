# English Reader Pro – Android

اپ اندروید: خواندن متن انگلیسی با لهجه‌های مختلف، OCR عکس، استخراج کلمات سخت، ترجمه، ذخیره صدا (WAV).

## ساخت APK بدون نصب چیزی روی کامپیوتر (GitHub Actions)
1. در github.com یک Repository جدید بسازید.
2. همه فایل‌های این پوشه را آپلود کنید (Add file → Upload files). پوشه مخفی `.github` گاهی آپلود نمی‌شود؛ اگر نشد:
   Add file → Create new file → نام: `.github/workflows/build.yml` → محتوای فایل build.yml همین پروژه را paste کنید.
3. تب **Actions** → «Build APK» → اگر خودش اجرا نشد، Run workflow.
4. بعد از ~۵–۱۰ دقیقه، در صفحه اجرا بخش **Artifacts** فایل `EnglishReaderPro-apk` را دانلود کنید. داخل zip فایل `app-debug.apk` است.
5. APK را روی گوشی ببرید و نصب کنید (اجازه «Install unknown apps» را بدهید).

## ساخت با Android Studio
پوشه را Open کنید، Sync کنید، بعد Build → Build APK(s). (به اینترنت/VPN برای دانلود Gradle و کتابخانه‌ها نیاز دارد.)

## نیازمندی‌ها روی گوشی
Android 10 یا بالاتر · موتور Google Text-to-Speech · برای ترجمه آفلاین بار اول اینترنت.
