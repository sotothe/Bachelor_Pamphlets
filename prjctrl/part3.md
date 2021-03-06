# جلسه سوم

## ادامه نمودار گانت

مثال) نمودار گانت پروژه لوله‌کشی گاز را رسم کنید. زمان انجام هر فعالیت 2 روز است.

![Slide_11-1](/prjctrl/images/s11-1.jpg)

![Slide_11-2](/prjctrl/images/s11-2.jpg)

پاسخ:

![Slide_12](/prjctrl/images/s12.jpg)

### اشکالات نمودار گانت

1. زمان انجام تمام فعالیت‌ها را باید داشته باشیم.
2. اگر در زمان یکی از فعالیت‌ها تغییری ایجاد شود باید نمودار را از ابتدا بکشیم.

## نمودارهای شبکه

نمودارهای شبکه ابزار قدرتمندی می‌باشند که برای رسمشان نیاز به دانستن زمان نمی‌باشد و به دو صورت زیر می‌باشند.

<div style="text-align:left">
`AON (Activity On Node)`
<br/><br/>
`AOA (Activity On Arrow)`
</div>

### شبکه AON

در این شبکه هر فعالیت به صورت یک مستطیل یا Box نمایش داده می‌شود.

مثال) شبکه AON مثال روزنامه را بکشید.

![Paper_1](/prjctrl/images/p1.jpg)

مثال) نمودار AON جدول زیر را بکشید.

![Slide_13-1](/prjctrl/images/s13-1.jpg)

پاسخ:

![Slide_13-2](/prjctrl/images/s13-2.jpg)

همانطور که دیده می‌شود چون در مسیر {A-D , F} پیشنیازی A برای H نشان داده شده است، نیازی به رسم بردار قرمز رنگ نمی‌باشد.

![Slide_14](/prjctrl/images/s14.jpg)

### شبکه AOA

در این شبکه فعالیت‌ها بر روی پیکان‌ها نمایش داده می‌شوند و هر دایره نشان‌دهنده یک رویداد می‌باشد.

#### نکته‌ها

- از هر گره چندین فعالیت می‌توانند آغاز شوند و چندین فعالیت می‌توانند به آن ختم شوند.
- شماره گره آغازین باید حتماً کوچکتر از شماره گره پایانی باشد.
- بین دو دایره مشخص تنها مجاز به رسم یک فعالیت هستیم.

مثال) فعالیت‌های A و B پیشنیاز C هستند. نمودار AOA این پروژه را بکشید.

![Paper_2](/prjctrl/images/p2.jpg)

مثال) پروژه‌ای 5 فعالیت A و B و C و D و E دارد. فعالیت‌های A و B پیشنیاز C و فعالیت D پیشنیاز E می‌باشد. نمودار AOA آن را رسم کنید.

![Paper_3](/prjctrl/images/p3.jpg)
