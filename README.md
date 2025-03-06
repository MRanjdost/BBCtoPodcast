# BBDtoPodcast - تبدیل اخبار BBC به پادکست با n8n

## توضیحات پروژه
این پروژه یک وورکفلو اتوماسیون قدرتمند با استفاده از ابزار [n8n](https://n8n.io/) است که اخبار سایت BBC را استخراج کرده، با هوش مصنوعی (مانند Google Gemini Pro و Hugging Face) پردازش می‌کند و آن‌ها را به فایل‌های صوتی پادکست تبدیل می‌کند. هدف این پروژه ارائه یک راهکار ساده و بدون کدنویسی برای تولید محتوای صوتی از منابع خبری است که می‌تواند برای یوتیوبرها، پادکسترها یا علاقه‌مندان به اتوماسیون مفید باشد.

این ایده در یک ویدیو یوتیوب آموزش داده شده که قدم‌به‌قدم مراحل ساخت این وورکفلو رو نشون می‌ده. برای مشاهده ویدیو و یادگیری بیشتر، [اینجا کلیک کنید](https://www.youtube.com/watch?v=Z4MaAM6B3S4&list=PLVEs0W-dLsDEmO1HwGI4bTTEGoXdiYKHG&index=5).

## ویژگی‌ها
- استخراج خودکار اخبار از سایت BBC.
- پردازش و تحلیل اخبار با هوش مصنوعی.
- تبدیل متن به گفتار با استفاده از مدل‌های پیشرفته مثل Google Gemini Pro و [Hugging Face MMS-TTS](https://huggingface.co/facebook/mms-tts-eng).
- خروجی به صورت فایل صوتی باکیفیت برای استفاده در پادکست.
- طراحی بدون نیاز به کدنویسی، مناسب برای همه.

## پیش‌نیازها
برای اجرای این پروژه، به موارد زیر نیاز دارید:
- **n8n**: آخرین نسخه از n8n روی سرور محلی یا ابری نصب شده باشد. [نصب n8n](https://docs.n8n.io/).
- **حساب API**: دسترسی به APIهای هوش مصنوعی مثل Google Gemini یا Hugging Face (کلید API لازم است). مدل تبدیل متن به گفتار استفاده‌شده: [Hugging Face MMS-TTS](https://huggingface.co/facebook/mms-tts-eng).
- **نرم‌افزار ضبط دسکتاپ**: برای تست و ضبط ویدیوی آموزشی (مثل OBS Studio).
- **اتصال اینترنت**: برای دسترسی به داده‌های BBC و پردازش آنلاین.

## نصب و راه‌اندازی
1. **کپی کردن ریپازیتوری:**
   - این پروژه رو از گیت‌هاب دانلود کنید:
