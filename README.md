## Contents
-  [Search Operators](#-search-operators)
-  [URL Modifiers](#-url-modifiers)
-  [Documents and Files](#-documents-and-files)
-  [Cameras and Webcams](#-cameras-and-webcams)
-  [Control Panels](#control_knobs-control-panels)
-  [Directories](#card_index_dividers-directories)
-  [Email](#-email)
-  [Google Drive](#card_file_box-google-drive)
-  [IoT Devices](#printer-iot-devices)
-  [Login](#-login)
-  [Movies](#-movies)
-  [Network Devices](#-network-devices)
-  [WordPress](#writing_hand-wordpress

# Search Operators
| Оператор         | Опис                                                                                                              | Синтаксис                               | Приклад                           |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------ | ------------------------------------ | --------------------------------- |
| ()               | Групування кількох термінів або операторів. Дозволяє створювати складні вирази                                                           | (&lt;term> or &lt;operator>)         | inurl:(html \| php)               |
| *                | Шаблон (wildcard). Відповідає будь-якому слову                                                                                               | &lt;text> * &lt;text>                | How to * a computer               |
| ""               | Задане ключове слово має збігатися точно. *Нечутливий до регістру*                                                               | "&lt;keywords>"                      | "google"                          |
| m..n / m...n     | Пошук у діапазоні чисел. *n* має бути більшим за *m*                                                            | &lt;number>..&lt;number>             | 1..100                            |
| -                | Документи, що відповідають оператору, виключаються. *Оператор НЕ*                                                           | -&lt;operator>                       | -site:youtube.com                 |
| +                | Включити документи, що відповідають оператору                                                                                | +&lt;operator>                       | +site:youtube.com                 |
| \|               | Логічний *АБО-оператор*. Достатньо збігу лише одного оператора, щоб загальний вираз спрацював                     | &lt;operator> \| &lt;operator>       | "google" \| "yahoo"               |
| ~                | Пошук синонімів заданого слова. Не підтримується Google                                                           | ~&lt;word>                           | ~book                             |
| @                | Виконати пошук лише на вказаній соціальній платформі. Краще використовувати **site**                                            | @&lt;socialmedia>                    | @instagram                        |
| after            | Пошук документів, опублікованих / проіндексованих після вказаної дати                                                            | after:&lt;yy(-mm-dd)>                | after:2020-06-03                  |
| allintitle       | Те саме, що **intitle**, але дозволяє кілька ключових слів, розділених пробілом                                                    | allintitle:&lt;keywords>             | allintitle:dog cat                |
| allinurl         | Те саме, що **inurl**, але дозволяє кілька ключових слів, розділених пробілом                                                      | allinurl:&lt;keywords>               | allinurl:search com               |
| allintext        | Те саме, що **intext**, але дозволяє кілька ключових слів, розділених пробілом                                                     | allintext:&lt;keywords>              | allintext:math science university |
| AROUND           | Пошук документів, у яких перше слово знаходиться на відстані до *n* слів від другого і навпаки                 | &lt;word1> AROUND(&lt;n>) &lt;word2> | google AROUND(10) good            |
| author           | Пошук статей, написаних вказаним автором (якщо застосовно)                                                            | author:&lt;name>                     | author:Max                        |
| before           | Пошук документів, опублікованих / проіндексованих до вказаної дати                                                           | before:&lt;yy(-mm-dd)>               | before:2020-06-03                 |
| cache            | Пошук у кешованій версії вказаного вебсайту. Використовує кеш Google                                          | cache:&lt;domain>                    | cache:google.com                  |
| contains         | Пошук документів, які містять посилання на вказаний тип файлу. Не підтримується Google                                             | contains:&lt;filetype>               | contains:pdf                      |
| date             | Пошук документів, опублікованих протягом останніх *n* місяців. Не підтримується Google                                       | date:&lt;number>                     | date:3                            |
| define           | Пошук визначення заданого слова                                                                              | define:&lt;word>                     | define:funny                      |
| ext              | Пошук певного типу файлу                                                                                           | ext:&lt;documenttype>                | ext:pdf                           |
| filetype         | Див. **ext**                                                                                                         | filetype:&lt;documenttype>           | filetype:pdf                      |
| inanchor         | Пошук заданого ключового слова в якорях вебсайту                                                                      | inanchor:&lt;keyword>                | inanchor:security                 |
| index of         | Пошук документів, що містять прямі посилання на завантаження                                                                         | index of:&lt;term>                   | index of:mp4 videos               |
| info             | Пошук інформації про вебсайт                                                                                   | info:&lt;domain>                     | info:google.com                   |
| intext           | Ключове слово має бути в тексті документа                                                                          | intext:&lt;keyword>                  | intext:news                       |
| intitle          | Ключове слово має бути в заголовку документа                                                                         | intitle:&lt;keyword>                 | intitle:money                     |
| inurl            | Ключове слово має бути в URL документа                                                                           | inurl:&lt;keyword>                   | inurl:sheet                       |
| link / links     | Пошук документів, чиї посилання містять задане ключове слово. Корисно для пошуку документів, які посилаються на конкретний сайт | link:&lt;keyword>                    | link:google                       |
| location         | Показати документи на основі вказаного місцезнаходження                                                                               | location:&lt;location>               | location:USA                      |
| numrange         | Див. **m..n**                                                                                                        | numrange:&lt;number>-&lt;numbe-  [Оператори пошуку](#-search-operators)
-  [Модифікатори URL](#-url-modifiers)
-  [Документи та файли](#-documents-and-files)
-  [Камери та веб-камери](#-cameras-and-webcams)
-  [Панелі керування](#control_knobs-control-panels)
-  [Каталоги](#card_index_dividers-directories)
-  [Електронна пошта](#-email)
-  [Google Диск](#card_file_box-google-drive)
-  [Пристрої IoT](#printer-iot-devices)
-  [Вхід](#-login)
-  [Фільми](#-movies)
-  [Мережеві пристрої](#-network-devices)
-  [WordPress](#writing_hand-wordpress)r>     | numrange:1-100                    |
| OR               | Див. **\|**                                                                                                          | &lt;operator> OR &lt;operator>       | "google" OR "yahoo"               |
| phonebook        | Пошук пов'язаних номерів телефонів із вказаним ім'ям                                                          | phonebook:&lt;name>                  | phonebook:"william smith"         |
| relate / related | Пошук документів, пов'язаних із вказаним вебсайтом                                                               | relate:&lt;domain>                   | relate:google.com                 |
| safesearch       | Виключити дорослий контент, наприклад порнографічні відео                                                                        | safesearch:&lt;keyword>              | safesearch:sex                    |
| source           | Пошук на конкретному новинному сайті. Краще використовувати **site**                                                                      | source:&lt;news>                     | source:theguardian                |
| site             | Пошук на вказаному сайті. Аргументом може бути лише домен верхнього рівня, наприклад **com, net** тощо                     | site:&lt;domain>                     | site:google.com                   |
| stock            | Пошук інформації про біржову акцію                                                                              | stock:&lt;stock>                     | stock:dax                         |
| weather          | Пошук інформації про погоду у вказаному місці                                                           | weather:&lt;location>                | weather:Miami                     |


# URL Modifiers
Додаються як параметр в кінці URL сторінки результатів пошуку (SERP).
| Модифікатор                   | Опис                          | Параметр          | Приклад                                              |
| -------------------------- | ------------------------------------ | --------------- | ---------------------------------------------------- |
| Пошук додатків (App Search)                 | Активувати фільтр пошуку додатків           | &tbs=app_price:free (free) <br/> &tbs=app_price:paid (paid) <br/> &tbs=app_os:1 (Android) <br/> &tbs=app_os:13 (iOS)   | https://www.google.com/search?q=star+wars&tbs=app_os:13      |
| Пошук блогів (Blog Search)                | Активувати фільтр пошуку блогів          | &tbs=blgt:b     | https://www.google.com/search?q=star+wars&tbs=blgt:b      |
| Відкрити локальний пошук (Bring Up Local Finder)      | Отримати локальні результати          | &tbm=lcl        | https://www.google.com/search?q=star+wars&tbm=lcl      |
| Пошук по країні (Country Search)             | Пошук по доменах країн               | &cr=country[CountryCode]    | https://www.google.com/search?q=star+wars&cr=countryAU       |
| Вимкнути фільтрацію результатів (Disable Filtering Of Results)  | Дає невідфільтровані результати    | &filter=0   | https://www.google.com/search?q=star+wars&filter=0      |
| Вимкнути персоналізовані результати (Disable Personalized Results)  | Дає неперсоналізовані результати    | &pws=0    | https://www.google.com/search?q=star+wars&pws=0      |
| Пошук на форумах (Forum Search)               | Активувати фільтр пошуку форумів         | &udm=18         | https://www.google.com/search?q=star+wars&udm=18      |
| Пошук зображень (Image Search)               | Активувати фільтр пошуку зображень         | &tbm=isch         | https://www.google.com/search?q=star+wars&tbm=isch      |
| Пошук новин (News Search)                | Активувати фільтр пошуку новин          | &tbm=nws <br/> &tbs=nrt:b (news from blogs) | https://www.google.com/search?q=star+wars&tbm=nws      |
| Без перенаправлення на країну (No Country Redirect)        | Перенаправляє на .com замість країнної URL         | /ncr         | https://www.google.com/ncr   |
| Пошук патентів (Patent Search)              | Активувати фільтр пошуку патентів         | &tbm=pts         | https://www.google.com/search?q=star+wars&tbm=pts      |
| Результати за останню годину (Results From Past Hour)     | Показує результати за останню годину        | &tbs=qdr:s (second) <br/> &tbs=qdr:n (minute) <br/> &tbs=qdr:h (hour) <br/> &tbs=qdr:d (day) <br/> &tbs=qdr:w (week) <br/> &tbs=qdr:m (month) <br/> &tbs=qdr:y (year)      | https://www.google.com/search?q=star+wars&tbs=qdr:h      |
| Пошук товарів (Shopping Search)              | Активувати фільтр пошуку товарів         | &tbm=shop         | https://www.google.com/search?q=star+wars&tbm=shop      |
| Пошук відео (Video Search)               | Активувати фільтр пошуку відео        | &tbm=vid         | https://www.google.com/search?q=star+wars&tbm=vid       |


# Disclaimer
ВИКОРИСТОВУЙТЕ НА ВЛАСНИЙ РИЗИК!
Google Dorking може використовуватися для кібербезпеки, тестування на проникнення та вразливості. Однак деякі дії можуть призвести до незаконної діяльності або порушення конфіденційних даних людей.

Для захисту використовуйте Tor Browser, а для ще кращого захисту – VPN.

# Documents and Files
- `filetype:pdf intitle:"Confidental"`
- `filetype:doc intitle:"Confidental"`
- `filetype:xls intitle:"Confidental"`
- `filetype:ppt intitle:"Confidental"`

# Cameras and Webcams
- `intitle:"D-Link" inurl:"/video.htm"`
- `intitle:"Linksys Viewer - Login" -inurl:mainFrame`
- `intitle:"Live View /-AXIS"`
- `intitle:"netcam watcher"`
- `intitle:"Network Camera NetworkCamera"`
- `intitle:"TP-LINK IP-Camera"`
- `intitle:"Webcam" inurl:WebCam.htm`
- `intitle:"webcamXP 5"`
- `intitle:webcamxp inurl:8080`
- `inurl:"axis-cgi/mjpg"`
- `inurl:"control/userimage.html"`
- `inurl:"/image/webcam.jpg"`
- `inurl:"/live/cam.html"`
- `inurl:"main.cgi?next_file=main_fs.htm"`
- `inurl:"/mjpg/video.mjpg"`
- `inurl:"MultiCameraFrame?Mode=Motion"`
- `inurl:"/out.jpg"`
- `inurl:"snapshot.cgi?user="`
- `inurl:top.htm inurl:currenttime`
- `inurl:"view/index.shtml"`
- `inurl:"view/indexFrame.shtml"`
- `inurl:"view/viewer_index.shtml"`
- `inurl:"viewerframe?mode=motion"`
- `inurl:"webcam.html"`

# Control Panels
- `intitle:"Admin Login"`
- `intitle:"Control Panel" inurl:/admin`
- `intitle:"Control Panel" inurl:/login`

# Directories
- `intitle:"Browse Directory"`
- `intitle:index.of`
- `intitle:"index of" database.properties`
- `intitle:"Index of" inurl:/parent-directory`
- `intitle:"Index of" inurl:/admin`
- `intitle:"Index of" inurl:/backup`
- `intitle:"Index of" inurl:/config`
- `intitle:"Index of" inurl:/logs`

# Email
- `filetype:txt @gmail.com OR @yahoo.com OR @hotmail.com OR @aol.com`
- `filetype:xls inurl:"email.xls"`

# Google Drive
- `site:drive.google.com confidential`

# IoT Devices
- `intitle:"Amazon Echo" "setup"`
- `intitle:"Baby Monitor" inurl:"/live"`
- `intitle:"Doorbell Camera" inurl:"/setup"`
- `intitle:"Google Home" "setup"`
- `intitle:"Router Login" inurl:/login`
- `intitle:"Smart Lighting Control Panel"`
- `intitle:"Sonos - Google Chrome"`
- `intitle:"Thermostat" inurl:"/status"`
- `intitle:"Smart TV" inurl:/cgi-bin/login`
- `intext:"SMART TV" inurl:password.txt`
- `inurl:"description.xml" "Philips hue bridge"`
- `inurl:"/smartlock" intitle:"Login"`

# Login
- `intitle:login`
- `intitle:login inurl:/admin`
- `intitle:login inurl:/login`
- `inurl:login`
- `inurl:"/admin/login.php"`
- `site:preprod.* * inurl:login`

# Movies
- `intitle:"index.of" (mp4|avi|mkv) "[movie name]" -html -htm -php -asp -jsp`
- `[movie name] site:drive.google.com intitle:wmv|mpg|avi|mp4|mkv|mov`
- `inurl:mkv+[movie name]`
- `inurl:mp4+[movie name]`

# Network Devices
- `intext:"printer meter"`
- `intitle:”Brother” intext:”View Configuration”`
- `intitle:"Device name" inurl:home.htm`
- `intitle:”Network Print Server” filetype:html`
- `intitle:”HP LaserJet” inurl:SSI/index.htm`
- `intitle:"open network devices"`

# WordPress
- `intext:”Powered by WordPress”`
- `intitle:”Login — WordPress”`
- `intitle:"powered by WordPress" version`
- `inurl:wp-content/plugins/`
- `inurl:/wp-content/plugins/revslider/`

