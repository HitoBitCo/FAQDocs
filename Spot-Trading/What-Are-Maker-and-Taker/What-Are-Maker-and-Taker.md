# سفارش‌گذار (Maker) و سفارش‌بردار (Taker) چیست؟

اگر نحوه محاسبه کارمزد ما را بررسی کرده باشید، می‌بینید که بسته به اینکه سفارش‌گذار یا سفارش‌بردار هستید، کارمزدهای متفاوتی دریافت می‌شود. سفارش‌گذارها کارمزدهای کمتری نسبت به سفارش بردارها پرداخت می‌کنند. هم سفارش‌گذار و هم سفارش‌بردار نقش اساسی در لیست سفارش صرافی دارند.
به زبان ساده:

-	سفارش‌گذار نقدینگی را برای معامله فراهم می‌کنند و بازاری برای یک رمزارز ایجاد می‌کنند.
-	سفارش‌بردار با انجام سفارش‌های باز در صرافی نقدینگی را حذف می‌کنند.
صرافی‌ها معمولاً سفارش‌گذار را تشویق می‌کنند تا نقدینگی را با کارمزد کمتری برای سفارش‌های خود در اختیار صرافی قرار دهند. بیایید عمیق‌تر به هر دو نقش بپردازیم.

## سفارش‌بردار:

-	وقتی سفارشی را ثبت می‌کنید که بلافاصله قبل از رفتن به لیست سفارش معامله انجام می‌شود، صرف‌نظر از اینکه شما یک سفارش را به طور جزئی یا کامل انجام می‌دهید شما یک سفارش‌بردار هستید.
-	معاملات حاصل از سفارش‌های بازار همیشه سفارش‌بردار هستند، زیرا سفارش‌های بازار هرگز در لیست سفارش نمی‌روند. به دلیل اینکه این معاملات در حال کاهش حجم از لیست سفارش هستند، بنابراین معاملات سفارش‌بردار هستند.
-	سفارش‌های قابل‌دسترسی از طریق API نیز همیشه سفارش‌بردار هستند.

## سفارش‌گذار:

-	وقتی سفارشی می‌دهید به طور جزئی یا کامل در لیست سفارش قرار می‌گیرد (مانند یک سفارش محدود که از طریق صفحه معاملات ثبت می‌شود)، هر معامله که بعد از آن در لیست سفارشات ثبت می‌شود، معاملات سفارش‌گذار خواهد بود.
-	این سفارش‌ها باعث افزایش حجم لیست سفارش‌ها می‌شود به عبارتی به ایجاد بازار کمک می‌کنند، بنابراین برای معاملات به عنوان سفارش‌گذار نامیده می‌شوند.
-	
> توجه: سفارش‌های از طریق API هم به‌عنوان سفارش‌گذار و هم به‌عنوان سفارش‌بردار می‌تواند ثبت شود.
