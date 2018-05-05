# فصل اول

## معرفی اوبونتو

قبل از اینکه شروع به نصب کنیم، بهتر است در مورد فلسفه و مفهوم کلی سیستم عامل اوبونتو صحبت کنیم.

### 

### تعاریف کلی

بهتر است قبل از پرداختن به اوبونتو، در مورد برخی تعاریف، مثل سیستم عامل و هسته، توضیح داده شود.

#### سیستم عامل چیست؟

سیستم عامل برنامه‌ای است که با سخت‌افزار ارتباط مستقیم دارد و امکان اجرای برنامه‌های کاربردی \(Application\) را روی بستر سخت‌افزاری ممکن می‌سازد.

#### هسته چیست؟

هسته نقش قسمت مرکزی و سطح پایین یک سیستم عامل را ایفا می‌کند و وظایفی مانند ارتباط با سخت‌افزار و بارگذاری درایورها را به دوش می‌کشد.

#### لینوکس چیست؟

برخلاف تصور خیلی از افراد، لینوکس تنها یک هسته با همان وظایف گفته شده است. بسیار کم پیش می‌آید که در کاربرد روزانه، به طور مستقیم با خود هستهٔ لینوکس ارتباط برقرار کنیم. با این حال، هسته نقش اصلی را در سیستم عامل بر عهده دارد.

#### چرا گنو/لینوکس آری، لینوکس نه؟

همان طور که گفته شد، لینوکس تنها یک هسته است و یک هسته به خودی خود هیچ کاری نمی‌تواند برای ما انجام دهد. ما برای برطرف‌کردن نیازهای روزانه به نرم‌افزارهای متعددی نیازمندیم. نرم‌افزارهایی که اکثراً از پروژهٔ گنو گرفته شده یا بر اساس فلسفهٔ نرم‌افزارهای آزاد و مجوز GNU GPL ساخته شده‌اند. برای همین، بهتر است این سیستم عامل \(و نه خود هسته\) را گنو/لینوکس بنامیم.

#### توزیع گنو/لینوکس چیست؟

گفتیم که پروژهٔ گنو/لینوکس از پیوستن ابزارهای گنو و هستهٔ لینوکس به وجود آمد. حالا فرض کنید که بخواهید آن را نصب کنید. چکار باید بکنید؟ در حالت قدیمی، باید یک متخصص کامل یونیکس باشید: هسته را بگیرید و کامپایل کنید، بعد یک دیسک را فرمت کنید و بوت سکتور را طوری تنظیم کنید که از این کرنل بوت شود. سپس دستورات \(برنامه‌های\) دیگر را روی آن کپی کنید و تمام وابستگی‌ها را هم رعایت کنید. چنین کاری برای بیش‌تر کاربران بسیار سخت است.  
برای حل این مشکل، افراد و شرکت‌هایی آمده‌اند و توزیع‌هایی \(Application\) را ساخته‌اند. در همان سال ۱۹۹۲ که هستهٔ لینوکس آمد، توزیع‌ها هم ظاهر شدند. کاربران هسته را به همراه چند برنامه اصلی و یک برنامه نصب کننده روی یکی دو فلاپی جا می‌دادند و بین دیگران پخش می‌کردند.

### 

### اوبونتو چیست؟

اوبونتو \(تلفظ به صورت oo'boontoo \) یک سیستم عامل کاملِ گنو/لینوکسی برای استفاده رومیزی است. اوبونتو \(مثل سایر گنو/لینوکس‌ها\) آزاد است و دارای پشتیبانی از طرف جامعهٔ کاربری و پشتیبانی حرفه‌ای از طرف شرکت سازندهٔ آن، Canonical است.

#### چطور اوبونتو و لینوکس به هم مربوط‌اند؟

اوبونتو یک سیستم عامل است که از لینوکس به عنوان هسته استفاده می‌کند. به طور ساده، لینوکس یک بخش از اوبونتو  است که وظیفهٔ مرکزی را به عهده دارد.  
جامعهٔ اوبونتو بر پایهٔ اندیشه‌های مطرح‌شده در بیانیهٔ اوبونتو فراهم آمده است. این‌که:

* نرم‌افزار باید رایگان باشد.

* نرم‌افزارها باید در زبان محلی کاربران قابل استفاده باشند و معلولیت‌ها را هم پوشش دهد تا اوبونتو برای بیش‌ترین افراد ممکن مورد استفاده قرار گیرد.

* کاربران باید آزادی تغییر نرم‌افزار به شیوهٔ دلخواه‌شان را داشته باشند.

برای همین، اوبونتو تنها یک سیستم عامل نیست و دارای سه بخش متفاوت است:

* فلسفه
* پروژهٔ نرم‌افزار مشترک جهانی
* سیستم عامل

این راهنما در تمام این مفاهیم در بخش‌های بعد گسترده می‌شود؛ اما در حال حاضر، مهم‌ترین چیز که باید به خاطر داشته باشید این است که اوبونتو بیش‌تر از یک نرم افزار است.

### فلسفهٔ اوبونتو

اوبونتو یک لغت قدیمی در زبان آفریقایی به معنای «یک نفر برای همه» یا «انسانیت با دیگران» است.

مجموعهٔ اوبونتو با سیستم عامل‌های دیگر متفاوت است، به دلیل اینکه روح انسانیت و جامعه را به دنیای رایانه می آورد. کاربران اوبونتو در یک باور عمیق هم‌عقیده‌اند که نرم‌افزار باید قابل دسترس برای همهٔ انسان‌ها، با هر زبان و رنگ پوست، توانایی جسمانی و درآمدی باشد.

### نرم‌افزار اختصاصی در مقابل نرم‌افزار آزاد و منبع‌باز

نرم‌افزارهای اختصاصی توسط یک شرکت طراحی می‌شوند، توسعه می‌یابند و فروخته می‌شوند. این نرم‌افزارها برای به‌دست‌آوردن سود فروخته می‌شوند و اکثراً فقط بر روی یک نوع از کامپیوترها کاربرد دارند. برای مثال، سیستم عامل‌های اختصاصی مانند Microsoft Windows و یا MacOS را در نظر بگیرید. کد منبع این سیستم‌ها در دسترس نیست و اگر شما سعی به تغییر یا توزیع آن را داشته باشید، متهم خواهید شد.

اوبونتو، به عبارت دیگر، یک نرم افزار اختصاصی نیست؛ به این دلیل که به صورت فعال توسط جامعهٔ FOSS نگهداری می شود.

#### FOSS چیست؟

FOSS مخفف عبارت Free/Libre Open Source Software و به معنی نرم‌افزار آزاد و متن‌باز است. نرم‌افزار FOSS به دلایل زیر با نرم‌افزارهای اختصاصی تفاوت دارد:

* استفادهٔ آزاد و رایگان
* اشتراک‌گذاری آزاد و رایگان
* توسعهٔ آزاد و رایگان

این یعنی شما بدون پرداخت هیچ مبلغی می‌توانید اوبونتو را دانلود و استفاده کنید. شما می‌توانید به صورت کاملاً قانونی از سی‌دی/دی‌وی‌دی های اوبونتو به هر تعداد که می‌خواهید، کپی کرده و بین دوستان و آشنایان‌تان توزیع کنید. حتا کد منبع سیستم عامل اوبونتو آزادانه در دسترس شماست و می‌توانید آن را با توجه به نیازهای خود تغییر دهید.

اوبونتو از مجوز عمومی همگانی GNU \(یا به طور ساده GPL\) استفاده می‌کند که به طور گسترده در جامعهٔ FOSS استفاده می‌شود. به همین دلیل، اوبونتو دارای آزادی‌هایی است که ذکر شد.

جی‌پی‌ال \(GPL\) توسط بنیان‌گذار پروژهٔ گنو و بنیاد نرم‌افزارهای آزاد، ریچارد استالمن، در سال ۱۹۸۹ نوشته شد و در آن به صراحت آمده است که کاربران برای اجرا، کپی، توزیع ، بازرسی، تغییر ، توسعه و بهبود نرم‌افزار ارائه‌شده آزاد هستند. گاهی GPL با  نام مستعار کپی‌لفت \(Copyleft\) می‌آید.

#### چطور ممکن است اوبونتو رایگان باشد؟

شما ممکن است تعجب کنید که در حال حاضر واقعاً چطور ممکن است اوبونتو رایگان باشد. آیا نکته و یا برخی هزینه‌های مخفی وجود دارد؟ به دو دلیل اوبونتو رایگان است.

##### مدیریت و بودجه‌بندی به پشتوانهٔ کنونیکال

اگر چه  اوبونتو توسط جامعهٔ FOSS نگهداری می‌شود، ولی مدیریت و تأمین بودجه از طریق شرکت خصوصی کنونیکال انجام می‌شود.  
کنونیکال پشتیبانی‌های تجاری را برای شرکت‌ها تامین می‌کند و از این راه درآمد دارد. درآمد حاصل از این پشتیبانی، برای توسعهٔ مستمر اوبونتو مصرف می‌شود. این توسعهٔ مستمر، شامل موارد زیر است:

* انتشار نسخه‌های جدید اوبونتو هر شش ماه یک‌بار

* به‌روزآوری‌های امنیتی

* سرورهای میزبانی وب برای جامعهٔ آنلاین اوبونتو

* دفاتر کنونیکال

##### اوبونتو از طریق جامعهٔ FOSS نگهداری می‌شود

از آنجایی که اوبونتو نرم‌افزاری کدباز است، کاربران برای دسترسی و تغییر کد منبع آزاد هستند و این به بهترشدن سیستم عامل برای همه کمک می‌کند.  
اوبونتو هم یک جامعهٔ جهانی است و هم یک پروژهٔ نرم‌افزاری مشترک. مردم در سرتاسر جهان می‌توانند زمان و توانایی‌های خود را با هم به اشتراک بگذارند و در فعالیت‌هایی مانند زیر کمک کنند:

* تست اشکالات نرم‌افزار

* ارسال مستندات کاربری

* طراحی اثر هنری

* ارائهٔ بازخورد

* نگارش جملاتی زیبا دربارهٔ اوبونتو

### چرا باید از اوبونتو استفاده کرد؟

* کار با اوبونتو ساده است.
* نصب نرم‌افزار، به‌روزرسانی سیستم عامل و پیدا کردن ابزارهای جدید با چند کلیک انجام پذیر است.
* محیط اصلی اوبونتو که یونیتی نام دارد، بسیار زیباست.
* آزاد است و برای همیشه رایگان باقی می‌ماند.
* اوبونتو با مشارکت کاربران‌اش ساخته شده و هرکسی می‌تواند برای بهتر شدن‌اش قدمی بردارد.
* اوبونتو از هستهٔ لینوکس استفاده می‌کند که طراحی بسیار منطقی و امنی دارد.
* اوبونتو به طور معمول ویروس نمی‌گیرد.
* اوبونتو با اکثر رایانه‌ها و لپتاپ‌ها کار می‌کند و در بیش‌تر مواقع حتی نیاز به نصب یک درایور هم ندارید.
* با برنامه و فایل‌های فعلی‌تان سازگار است. اکثر محتوای چندرسانه‌ای در اوبونتو قابل پخش است و بسیاری از برنامه‌ها، مثل فایرفاکس، کروم و اسکایپ، نسخه‌ای مناسب اوبونتو دارند.
* از بسیاری از زبان‌ها، از جمله زبان فارسی، به خوبی پشتیبانی می‌کند.
* پایدار و سرعت آن بالاست. اوبونتو کند نمی‌شود و لازم نیست هر چند وقت دوباره نصب‌اش کنید. به چندین گیگابایت رَم هم برای اجرا نیاز ندارد.

همیشه کسی برای کمک هست. اوبونتو در میان فارسی‌زبانان هم شناخته شده است و افراد زیادی در انجمن فارسی اوبونتو و کانال IRC اوبونتوی فارسی، بدون هیچ چشم‌داشتی، به شما کمک می‌کنند.

### نکاتی در مورد اوبونتو

کنونیکال نسخه‌های جدید اوبونتو را هر شش ماه یک بار، در ماه‌های آوریل و اکتبر، منتشر می‌کند. هر اوبونتو که منتشر می‌شود، یک شماره‌نسخه دارد که از سال و ماه انتشار آن تشکیل شده است. این راهنما به طور عمده برای اوبونتو ۱۴.۰۴ نوشته شده که در ماه آوریل سال ۲۰۱۴ منتشر شده است.

علاوه بر شماره، هر نسخه اوبونتو یک نام هم دارد که از ترکیب یک صفت و نام یک حیوان تشکیل می‌شود. برای مثال نام کد برای اوبونتو ۱۴.۰۴، Trusty Tahr است. همچنین اوبونتو ۱۴.۰۴ یک نسخهٔ LTS است.LTSها\(Long Term Support\) نسخه‌هایی از اوبونتو هستند که تقریباً هر دو سال یک‌بار \(طبق زمان‌بندی\) منتشر می‌شوند و برای ۵ سال بعد از آن پشتیبانی می‌شوند. نسخه‌های عادی ۹ ماه پشتیبانی دارند.
