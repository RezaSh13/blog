---
author: رضا شکری
type: image
featimg: obs-studio1.jpg
title: <div dir="rtl"> حل مشکل عدم اجرا شدن obs studio </div>
tags: [image]
category: [image]
layout: post-material-sidebar-right
gallery:
    - images:
      - filename: obs-studio2.jpg
        alttext:
---
<div dir="rtl"> 

بعد مدت‌ها یه اکانت اینستاگرام ساختم و مشغول به پست گذاشتم شدم و می‌خواستم لایو هم داشته باشم اما یه مشکلی که بود من صفحه دسکتاپ خودم رو می‌خواستم share کنم اما نه با دوربین و صد البته برنامه‌ای برای این کار پیدا کردم اما یه مشکلی داشت نیاز به برنامه obs studio داشت اما من هم قبلا این برنامه رو تست کرده بودم و بهم ارور می‌داد و می‌گفت درایور کارت گرافیک بروز نیست
</div>

{% include gallery.html %}


<div dir="rtl"> 

من هم قبلا دست از اجرای این برنامه برداشته بودم و سراغ برنامه‌هایی مثل SimpleScreenRecorder رفته بودم و با این برنامه کار مورد نیاز خودم رو انجام می‌دادم اما با این دیدم که برای share صفحه نیاز به برنامه obs studio دارم پس تصمیم گردم مشکلش رو حل کنم کمی که تو نت جستجو کردم متوجه شدم که اگه obs studio رو با پارامتر مناسبی در نظر بگیری بدون هیچ مشکلی اجرا میشه کافیه تو ترمینال به این صورت اجراش کنید:
</div>

<br> 


```yml
---
LIBGL_ALWAYS_SOFTWARE=1 obs
---
```

<br> 
<div dir="rtl"> 
البته من یه قدم پا رو فراتر گذاشتم و رفتم آیکون لانچ برنامه رو هم ویرایش کردم تا دیگه نیاز به ترمینال نباشه و متغیر بالا رو تو فایل لانچ گذاشتم.
</div>

<br> 

<img src="/blog/img/obs-studio3.jpg" alt="obs-studio" style="height: 651px; width:961px;" class="center"/>
