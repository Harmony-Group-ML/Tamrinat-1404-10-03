# Heart Disease Classification using Deep Learning (PyTorch)

## توضیحات پروژه
این پروژه یک نمونه از **استفاده از هوش مصنوعی برای تشخیص بیماری در یک عضو بدن** است.  
مدل با استفاده از **شبکه عصبی عمیق (Deep Learning)** و **PyTorch**، بیماری قلبی را در بیماران پیش‌بینی می‌کند.

- **عضو مورد بررسی:** قلب  
- **هدف:** پیش‌بینی وجود یا عدم وجود بیماری قلبی در بیماران  
- **دیتاست:** [Cleveland Heart Disease Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/heart-disease/processed.cleveland.data)  
- **مدل:** شبکه عصبی Feedforward ساده با PyTorch  
- **خروجی:** دقت مدل، Confusion Matrix و پیش‌بینی نمونه‌ها  

---

## ویژگی‌ها
- آموزش مدل با دیتاست واقعی بدون نیاز به فایل‌های محلی اضافی  
- استفاده از PyTorch و DataLoader برای آموزش شبکه عصبی  
- نمایش **Confusion Matrix** و دقت برای ارزیابی مدل  
- آماده اجرا در **Google Colab**  

---

## نصب وابستگی‌ها

قبل از اجرا، کتابخانه‌های زیر نصب شوند:

```bash
pip install torch torchvision pandas scikit-learn matplotlib
```

## اجرای پروژه
کلون کردن Repo:
```bash
git clone https://github.com/username/Heart-Disease-Classification-deepLearning-pytorch.git
```
## ورود به پوشه پروژه:
```bash
cd 
Heart-Disease-Classification-deepLearning-pytorch
```

## باز کردن نوت‌بوک:
```bash
Heart_Disease_Classification.ipynb
```
## اجرای سلول‌ها

- دانلود و بارگذاری دیتاست از اینترنت  
- آماده‌سازی داده‌ها و نرمال‌سازی  
- آموزش مدل با PyTorch  
- نمایش Accuracy و Confusion Matrix
  
## دیتاست

- دیتاست **Cleveland Heart Disease** شامل ۱۴ ویژگی و یک ستون هدف (`target`) است که مشخص می‌کند بیمار بیماری قلبی دارد یا خیر.  
- لینک دیتاست: [Cleveland Heart Disease Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/heart-disease/processed.cleveland.data)
  
## ویژگی‌ها

- `age` – سن  
- `sex` – جنسیت  
- `cp` – نوع درد قفسه سینه  
- `trestbps` – فشار خون در حالت استراحت  
- `chol` – کلسترول خون  
- `fbs` – قند خون ناشتا  
- `restecg` – ECG استراحت  
- `thalach` – حداکثر ضربان قلب  
- `exang` – درد قفسه سینه ناشی از ورزش  
- `oldpeak` – افت ST ناشی از ورزش  
- `slope` – شیب ST  
- `ca` – تعداد رگ‌های بزرگ با گرفتگی  
- `thal` – نوع تالاسمی  
- `target` – برچسب بیماری (0 = سالم، 1 = بیمار)
  
## خروجی‌ها

- **Accuracy:** دقت مدل روی داده‌های تست  
- **Confusion Matrix:** نمایش عملکرد مدل در دسته‌بندی سالم/بیمار  
- **پیش‌بینی نمونه‌ها:** نمونه‌هایی از پیش‌بینی مدل

## توجهات

- فایل نوت‌بوک: `Heart_Disease_Classification.ipynb`  
- دیتاست از اینترنت مستقیم لود می‌شود → نیازی به آپلود دستی نیست  
- پروژه آماده برای کلون و اجرا در Google Colab یا سیستم محلی است

## منابع

- [GitHub Repo مدل PyTorch اصلی](https://github.com/MarkMburu/Heart-Disease-Classification-deepLearning-pytorch)  
- [Cleveland Heart Disease Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/heart-disease/processed.cleveland.data)  
- [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)  
- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
