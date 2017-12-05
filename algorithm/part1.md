# بخش اول

### مرتبه زمانی:
در طراحی الگوریتم هدف استفاده از روش‌هایی برای کاهش مرتبه زمانی و کاهش تعداد گام‌های یک برنامه می‌باشد. مرتبه زمانی یا order مدت زمان اجرا یا همان تعداد گام‌های اجرای یک برنامه را نشان می‌دهد. مرتبه زمانی الگوریتم‌ها در دسته‌های زیر قرار می‌گیرند.

### شمارگام‌های یک برنامه:
برای محاسبه‌ی مرتبه‌ی زمانی باید شمار گام‌های یک برنامه محسابه شود، یعنی هر سطر از برنامه چند بار اجرا می‌شود. در ادامه با چند مثال شمار گام‌ها را محاسبه می‌کنیم.

حل معادلات بازگشتی به روش جایگزینی با استفاده از رابطه‌ی بازگشتی (با جایگذاری) از $$ n $$ شروع کرده و به عقب بر می‌گردیم تا به شرط خروجی یا مقدار اولیه رابطه بازگشتی برسیم.

## تقسیم و حل:
### حل مسائل با استفاده از تقسیم و حل
مسائل سنگین به مسائل کوچکتری تقسیم می‌شوند، هرکدام از این مسائل کوچک را زیر مسئله می‌گویند. در نهایت حل مسائل کوچک سریع‌تر و راحت از مسائل بزرگ می‌باشد.

سپس با ترکیب حل مسائل کوچک جواب مسئله بزرگ به دست می‌آید.

### حل مسئله جستجوی دودویی به روش تقسیم و حل:
این الگوریتم برای لیست مرتب ارائه شده است. همانطور که می‌دانید در لیست مرتب و نامرتب بدترین حالت جستجوی یک عدد روش خطی یا <span>
0#x200E; $$ o(n^2) $$ 
 </span> می‌باشد. اما در مورد لیست مرتب با جستجوی دودویی مرتبه زمانی $$ o(log\n) $$ خواهد بود.