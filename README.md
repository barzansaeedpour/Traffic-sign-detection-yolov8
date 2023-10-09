# Traffic Sign Detection 
#### Enhancing Road Safety, preparation of road maps, smart city, traffic efficienc


# سامانه هوش مصنوعی تشخیص علائم ترافیکی
#### افزایش ایمنی جاده، تهیه نقشه راه، شهر هوشمند، بهره وری ترافیک

در این مخزن گیت هاب، نسخه ای سبک از پروژه ما برای تشخیص علائم راهنمایی ارائه شده است.

In this git repository a light version of our Traffic Sign Detection project is presented.

نمونه تشخیص (Detection sample):


<img width= "70%" src='./files/prediciton.jpg'/>

<img width= "70%" src='./files/output.gif'/>


<br/>

کاربرد این سامانه:

سامانه هوش مصنوعی تشخیص علائم ترافیکی به عنوان یکی از کاربردهای مهم هوش مصنوعی در حوزه مهندسی ترافیک و راهنمایی و رانندگی دارای مزایای زیادی است. کاربردها و مزایا اصلی این سامانه به شرح زیر هستند:

1- ترافیک هوش مصنوعی: این سامانه‌ها به عنوان بخشی از ترافیک هوش مصنوعی و اینترنت اشیاء (IoT) در توسعه شهر هوشمند مورد استفاده قرار می‌گیرند.

2- افزایش ایمنی جاده: سامانه‌های تشخیص علائم ترافیکی به تشخیص دقیق و سریع علائم راهنمایی و رانندگی می‌پردازند. این تشخیص به کاهش تصادفات و حوادث رانندگی کمک می‌کند.

3- کاهش خطاهای انسانی: انسان‌ها ممکن است در برخی مواقع علائم راهنمایی را اشتباه بخوانند یا نادیده بگیرند. سامانه‌های هوش مصنوعی با تشخیص دقیق علائم به خطاهای انسانی پیشگیری می‌کنند.

4- افزایش بهره‌وری ترافیک: با دقیق‌تر شدن رانندگی و رعایت دقیق قوانین ترافیکی، ترافیک بهره‌وری بیشتری خواهد داشت و زمان رانندگی کاهش می‌یابد.

5- تسهیلات رانندگی خودروهای خودکار: در آینده، اتومبیل‌های خودکار به سیستم‌های تشخیص علائم ترافیکی نیاز دارند تا بهترین تصمیم‌ها را برای رانندگی ایمن اتومبیل‌ها بگیرند.

به طور کلی، سامانه هوش مصنوعی تشخیص علائم ترافیکی به بهبود ایمنی و بهره‌وری در محیط‌های حمل و نقل عمومی و شهر هوشمند کمک می‌کند و به کاهش تصادفات و مشکلات ترافیکی می‌انجامد.


# Dataset:

The dataset has uploaded to Kaggle, and you can download it in the following address:

- https://www.kaggle.com/datasets/barzansaeedpour/traffic-sign-detection

class names:

| Label | Persian | English | Image |
|----------|----------|----------|----------|
| avalin-pich-be-chap | اولین پیچ به چپ | first curve to the left | <img width="50%" src='./files/اولین-پیچ-به-چپ .png'/>|
| avalin-pich-be-rast | اولین پیچ به راست | first curve to the right | <img width="50%" src='./files/اولین-پیچ-به-راست.png'/> |
| dast-andaz | دست انداز | bump | <img width="50%" src='./files/دست-انداز.png'/> |
| dor-bargardan | دور برگردان | u turn | <img width="50%" src='./files/'/> |
| dor-zadan-mamnoe | دور زدن ممنوع | u turn prohebited | <img width="50%" src='./files/'/> |
| dorbine-sabte-takhalofat | دوربین ثبت تخلفات | speed camera | <img width="50%" src='./files/'/> |
| faghat-obor-az-chap-mojaz | فقط عبور از چپ مجاز | compulsory keep left | <img width="50%" src='./files/'/> |
| faghat-obor-az-rast-mojaz | فقط عبور از راست مچاز | compulsory keep right | <img width="50%" src='./files/'/> |
| gardesh-be-rast-mamnoe | گردش به راست ممنوع | right turn prohebited | <img width="50%" src='./files/'/> |
| hadeaksar-sorat-mojaz-100 | حداکثر سرعت مجاز 100 | speed limit 100 | <img width="50%" src='./files/'/> |
| hadeaksar-sorat-mojaz-110 | حداکثر سرعت مجاز 110 | speed limit 110 | <img width="50%" src='./files/'/> |
| hadeaksar-sorat-mojaz-40 | حداکثر سرعت مجاز 40 | speed limit 40 | <img width="50%" src='./files/'/> |
| hadeaksar-sorat-mojaz-50 | حداکثر سرعت مجاز 50 | speed limit 50 | <img width="50%" src='./files/'/> |
| hadeaksar-sorat-mojaz-60 | حداکثر سرعت مجاز 60 | speed limit 60 | <img width="50%" src='./files/'/> |
| hadeaksar-sorat-mojaz-80 | حداکثر سرعت مجاز 80 | speed limit 80 | <img width="50%" src='./files/'/> |
| hadeaksar-sorat-mojaz-85 | حداکثر سرعت مجاز 85 | speed limit 85 | <img width="50%" src='./files/'/> |
| hadeaksar-sorat-mojaz-95 | حداکثر سرعت مجاز 95 | speed limit 95 | <img width="50%" src='./files/حداکثر سرعت 95.jpg'/> |
| hedayat-be-chap | هدایت به چپ | guide to left | <img width="50%" src='./files/'/> |
| hedayat-be-rast | هدایت به راست | guide to right | <img width="50%" src='./files/'/> |
| istadan-mamnoe | ایستادن ممنوع | no stopping or standing | <img width="50%" src='./files/'/> |
| khatar | خطر | danger | <img width="50%" src='./files/'/> |
| khatare-rizeshe-sang | خطر ریزش سنگ | falling rocks | <img width="50%" src='./files/'/> |
| obor-az-har-do-samt-mojaz | عبور از هر دو سمت مجاز | either side | <img width="50%" src='./files/'/> |
| obour-haywanate-ahli | عبور حیوانات اهلی | possibility of cattle on road | <img width="50%" src='./files/'/> |
| parking | پارکینگ | parking | <img width="50%" src='./files/'/> |
| pich-be-chap | پیچ به چپ | left turn | <img width="50%" src='./files/پیچ-به-چپ.png'/> |
| pich-be-rast | پیچ به راست | right turn | <img width="50%" src='./files/پیچ-به-راست.png'/> |
| rayate-haghe-taghadom | رعایت حق تقدم | give way | <img width="50%" src='./files/رعایت-حق-تقدم.png'/> |
| sebghat-azad | سبقت آزاد | overtaking allowed | <img width="50%" src='./files/پایان-سبقت-ممنوع.jpg'/> |
| sebghat-mamnoe | سبقت ممنوع | no overtaking | <img width="50%" src='./files/سبقت-ممنوع.png'/> |
| taghatoe | تقاطع | intersection | <img width="50%" src='./files/تابلوی تقاطع.jpg'/> |
| voroud-be-rahe-asli-az-chap | ورود به راه اصلی از چپ | side road left | <img width="50%" src='./files/ورود-به-راه-اصلی-از-چپ.png'/> |
| voroud-be-rahe-asli-az-rast | ورود به راه اصلی از راست | side road right | <img width="50%" src='./files/ورود-به-راه-اصلی-از-راست.png'/> |
| voroud-be-rahe-asli-az-rast2 | ورود به راه اصلی از راست 2 | side road right 2 | <img width="50%" src='./files/ورود-به-راه-اصلی-از-راست-2.png'/> |
| voroud-mamenoe | ورود ممنوع | no entry | <img width="50%" src='./files/ورود-ممنوع.png'/> |


# Instruciton:


