# alias یا نام ساختگی

## محتویات درس

گاهی تایپ کردن دوباره و دوباره‌ی یک دستور خسته‌کننده می‌شود. گاهی هم تایپ یک دستور بلند برای چندین و چند بار این حس مزخرف را تداعی می‌کند و اینجاست که اهمیت اِلیِسْ یا نام‌های ساختگی مشخص می‌شود. برای ایجاد یک الیس برای یک دستور کافیست که اسم الیس رو به همراه دستور وارد خط فرمان کنید.

```$ alias foobar='ls -la'```

اکنون به جای تایپ ls -la می‌توانید foobar را تایپ کنید و دقیقاً همان فرمان را اجرا کنید. البته لازم است که بدانید که دستور بالا، تا زمانی که سیستم را ری‌استارت کنید، جوابگو است و چیزی برای استفاده مجدد در شروع‌مجدد سیستم، ذخیره نمی‌شود. به عبارت ساده‌تر بعد از ری‌استارت سیستم اگر دستور foobar را تایپ کنید، خط فرمان به شما می‌گوید که چنین فرمانی وجود خارجی ندارد. اگر می‌خواهید الیس‌ها بعد از شروع‌مجدد سیستم باز هم در دسترس شما باشند، بایستی آن‌ها به فایل زیر و یا فایل‌های مشابه‌اش اضافه کنید.

```~/.bashrc```

برای حذف یک نام ساختگی هم از دستور  unalias می‌توانید کمک بگیرید:

```$ unalias foobar```

## تمرین

چند الیس بسازید و حذف کنید تا دستتان راه بیفتد.

## سؤال آزمون

بایستی چه دستوری را برای ساخت یک الیس یا نام ساختگی به کار ببرید.

## جواب آزمون

alias
