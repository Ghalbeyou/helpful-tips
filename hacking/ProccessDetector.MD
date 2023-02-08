# `/hacking/ProccessDetector` پروسس دتکتور 
این نرم افزار در پایتون نوشته شده است و با استفاده از آن میتوانید ببینید که آیا نرم افزاری اجرا هست یا خیر که بسیار برای افراد زیادی مناسب است.
> **`نیازمندی ها`** 
>
> 1. پایتون
> 2. مهفوم کدنویسی

> ## بخش **`1`**: **کد مربوطه و تفسیر آن**

کد: 
```py
import psutil
import sys

for proc in psutil.process_iter():
    try:
        if proc.name() == "Taskmgr.exe": # If process detected.
            proc.kill()
            print("Task Manager process closed.")
            sys.exit()
    except (psutil.NoSuchProcess, psutil.AccessDenied, psutil.ZombieProcess):
        pass

print("Task Manager not detected.") # If process not detected.
# Credit: Decation2
```
همونطور که میبینید ابتدا ماژول های psutil و sys رو ایمپورت میکنیم و سپس برای هر تسک توی لیست بررسی میکنیم
حال؛ اگر اسم تسک Taskmgr.exe بود تسک رو بکش و بگو تسک منیجر بسته شد
درغیر اینصورت بگو تسک منیجر وجود نداشته.
> ## بخش **`2`**: **چرا؟**
این نرم افزار میتونه کمک زیادی کنه برای اینکه بتونید از کرک نرم افزارتون جلوگیری کنید و یا ....


> **`!`** این کد توسط [@Decation2](https://www.github.com/Decation2) نوشته شده است. **`!`**

> **آیا گم شدی؟**
>
> [**آره** ->](README.md)
>
> **`لطفا اگر از این ریپو خوشتون اومد بهش استار بدید.`**