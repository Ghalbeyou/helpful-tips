# `/github/PR.MD` چطور یک PR باز کنم؟
پی.آر یا پول ریکیوست یک سیستمی است که گیتهاب برای ایجاد تغییرات و انتشار آن ساخته است. برای باز کردن یک پول ریکویست یا پی.آر مراحل زیر را در پی بگیرید.

> **`نیازمندی ها`** 
>
> 1. نرم افزار CLI گیت


> ## مرحله **`1`**: **فورک (Fork)**
ابتدا مخزن مدنظر را فورک کنید.
> ![عکس](https://raw.githubusercontent.com/Ghalbeyou/helpful-tips/main/Assets/github/PR/fork.png)
*Fork*

> ## مرحله **`2`**: **کلون**
ابتدا لینک کلون را در حساب خود کپی کنید
> ![عکس](https://raw.githubusercontent.com/Ghalbeyou/helpful-tips/main/Assets/github/PR/clone.png)
*کلون با مرورگر*

سپس در ترمینال همون آدرس رو وارد کنید و یک **.git** به آخرش اضافه کنید:
> ![عکس](https://raw.githubusercontent.com/Ghalbeyou/helpful-tips/main/Assets/github/PR/command.png)
*کلون با ترمینال*

> ## مرحله **`3`**: **انتقال به پوشه کلون شده**
برای انتقال کد زیر را وارد کنید:
> ![عکس](https://raw.githubusercontent.com/Ghalbeyou/helpful-tips/main/Assets/github/PR/locating.png)
*انتقال*

> **`!`** بجای **articles-of-the-week** اسم مخزن فورک شده را وارد کنید. **`!`**

> ## مرحله **`4`**: **ساخت برنچ (branch)**

اکنون یک برنچ بسازید مثل زیر:
> ![عکس](https://raw.githubusercontent.com/Ghalbeyou/helpful-tips/main/Assets/github/PR/branch.png)
*Branch*

> **`!`** بجای **my-article** اسم برنچ مورد نظر را وارد کنید. **`!`**

> ## مرحله **`5`**: **ایجاد تغییرات**
اکنون تغییرات مدنظر را وارد کنید و با کد زیر آنرا منتشر کنید:

> ![عکس](https://raw.githubusercontent.com/Ghalbeyou/helpful-tips/main/Assets/github/PR/commit.png)
*Commit*

> **`!`** بجای **Adding an article to ...** عنوان مورد نظر را وارد کنید. **`!`**

> ## مرحله **`6`**: **انتشار تغییرات**
برای انتشار تغییرات ابتدا کد زیر را وارد میکنیم:

> ![عکس](https://raw.githubusercontent.com/Ghalbeyou/helpful-tips/main/Assets/github/PR/push.png)
*Push*

همونظور که میبیند اسم برای ما **origin** هست؛ بنابراین ما با این نام تغییرات خودرا منتشر میکنیم:

> ![عکس](https://raw.githubusercontent.com/Ghalbeyou/helpful-tips/main/Assets/github/PR/push2.png)
*Push*

> ## مرحله **`7`**: **ایجاد پی.آر**
برای اینکار؛ وارد مخزن فورک شده بشید و در اونجا یک دکمه به نام "Compare" خواهید دید. روی آن بزنید:

> ![عکس](https://raw.githubusercontent.com/Ghalbeyou/helpful-tips/main/Assets/github/PR/pr.png)
*Pull request*

حال در این قسمت عنوان و توضیحات مربوطه را وارد کنید. بسیار ساده

> ![عکس](https://raw.githubusercontent.com/Ghalbeyou/helpful-tips/main/Assets/github/PR/final.png)
*Pull request*

> **آیا گم شدی؟**
>
> [**آره** ->](README.MD)
>
> **`لطفا اگر از این ریپو خوشتون اومد بهش استار بدید.`**