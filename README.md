# netmeli

فایل main.yml رو دانلود کنید

برین  تو گیت هاب یک repository جدید درست کنید

بعد برید تو تب actions گزینه set up a workflow yourself رو بزنید

کد توی main.yml رو اینجا کپی کنید بعد Commit changes رو بزنید

حالا برگردید توی تب actions از sidebar چپ Download Large File, Split, and Commit to Repo رو انتخاب کنید

بعد run workflow لینک رو توی باکس paste کنید بعد run کنید

فایل ها توی فولدر chunks دانلود میشن توی تب code

برای دانلود اگه حجم کمه توی تب code گزینه code رو بزنید بعد دانلود zip ولی برای حجم بالاتر بعضی مواقع مشکل ایجاد میکنه

برای دانلود مطمن تر برید تو پوشه chunks روی هر chunk کلیک کنید و view raw یا download raw file رو بزنید( میتونید لینک view raw رو تو دانلود منیجر کپی کنید ولی اگر دانلود نشد به بار رو فایل بزنید دانلود توی مرورگر شروع بشه بعد کنسل کنید و لینکشو توی دانلود منیجر کپی کنید)

بعد از دانلود همه فایل های chunk رو تو یه پوشه بزارید و توی اون پوشه نسبت به سیستم بخش بعدی رو انجام بدین و به جای file.format اسم فایل و فرمت فایل رو بزارید مثلا a.mp4

برای ران کردن توی همون پوشه میتونید کلیک راست کنید و open in termmianl رو بزنید یا توی address bar بالا cmd رو تایپ کنید و enter رو بزنید تا فایل شما اماده بشه



Linux, macOS

cat chunk_* > file.format




Windows PowerShell 

cmd /c copy /b chunk_* file.format




Windows  PowerShell 7+

Get-Content chunk_* -AsByteStream | Set-Content file.format -AsByteStream




cmd

copy /b chunk_* file.format




نکته : 

قبل فرستادن لینک بعدی پوشه chunks رو پاک کنید که فایل های قبلی پاک بشه

ممکنه برای set up به فیلتر شکن نیاز بشه(برای ساختن workflow) ولی برای دانلود نیازی نیست

من با نت ایرانسل هیچ مشکلی نداشتم ولی با نتای دیگه هم نباید مشکلی باشه

اگر مشکلی به بود ایدی @Hailofblades تو تلگرام پیام بدید
