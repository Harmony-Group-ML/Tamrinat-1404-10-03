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
