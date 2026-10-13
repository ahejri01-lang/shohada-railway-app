ساخت APK فقط با گوشی از طریق GitHub Actions

۱) در مرورگر گوشی وارد https://github.com شوید و حساب بسازید یا وارد شوید.
۲) یک repository جدید بسازید؛ نام پیشنهادی shohada-railway-app.
۳) فایل‌های این پروژه را در repository بارگذاری کنید. پوشه مخفی .github/workflows هم باید بارگذاری شود.
۴) در مخزن، تب Actions را باز کنید و workflow با نام Build Android APK را انتخاب کنید؛ سپس Run workflow را بزنید.
۵) بعد از موفقیت اجرا، وارد همان اجرای workflow شوید و در بخش Artifacts فایل shohada-railway-debug-apk را دانلود کنید.
۶) فایل Artifact یک ZIP است؛ آن را باز کنید تا app-debug.apk را بردارید و روی گوشی نصب کنید.

اگر GitHub در موبایل آپلود پوشه‌ها را سخت کرد، در مرورگر گزینه Desktop site را فعال کنید. در مخزن باید app، build.gradle، settings.gradle، gradle.properties و .github/workflows/android-apk.yml موجود باشند.

این APK برای تست است و debug امضا شده؛ برای انتشار رسمی به فرایند امضای release نیاز است. پنل مدیریت موجود در اپ نمایشی است، رمز 1234 دارد و داده‌ها فقط روی همان دستگاه ذخیره می‌شوند. اطلاعات حساس دانش‌آموزان را وارد نکنید.
