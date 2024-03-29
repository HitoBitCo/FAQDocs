# نحوه ایجاد API

ایجاد یک API به شما امکان می‌دهد از طریق زبان‌های برنامه‌نویسی و پلتفرم‌های دیگر به سرورهای هیتوبیت متصل شوید؛ داده‌ها را از هیتوبیت منتقل و در پلتفرم دیگری استفاده کنید؛ کیف پول فعلی و داده‌های تراکنش خود را مشاهده کنید؛ معامله انجام دهید و دارایی خود را در برنامه‌های شخص ثالث واریز و برداشت کنید، ساخت API فرایند ساده‌ای است که تنها در پنج دقیقه انجام می‌شود.

## چگونه در هیتوبیت API خود را ایجاد کنیم؟

**1.**	پس از ورود به هیتوبیت، به حساب کاربری خود رفته و بر روی   **[مدیریت APIها]** کلیک کنید.

![مدیریت APIها](./Images/API-management.png)

**2.**	یک نام برای کلید API خود انتخاب و بر روی **[ایجاد API]** کلیک کنید.

![نام کلید API](./Images/create-API.png)

> **توجه:** <br>قبل از ایجاد  API، باید شناسایی دو عاملی (2FA) را در حساب خود فعال کنید.

**3.**	کد دریافت‌شده در موبایل را در قسمت **[کد تایید]** و رمز دریافت‌شده از Google Authenticator را در **[کد احراز هویت]** وارد کنید. پس از تکمیل مقادیر، بر روی گزینه **[ارسال]** کلیک کنید.

![تایید امنیتی API](./Images/security-verification-for-create-API.png)

**4.**	اکنون API شما ایجاد شده است و بر اساس توضيحات زیر می‌توانید از آن استفاده کنید.

![کلیدها و محدودیت‌های API](./Images/API-keys-and-IP-restriction.png)

- **استفاده از کلید API:** برای استفاده از **کلید API** آن را کپی و در قسمت موردنظر جای‌گذاری کنید. همچنین می‌توانید برای این منظور کد QR را اسکن کنید.<br>
- **نگهداری کلید مخفی:** **کلید مخفی خود را یادداشت و در جای مناسب ذخیره کنید** زیرا دیگر نمایش  داده **نخواهد** شد. این کلید را با کسی به اشتراک نگذارید. اگر کلید مخفی خود را فراموش کنید باید API را حذف و یک API جدید ایجاد کنید.<br>
- **محدودیت‌های API:**  در این بخش گزینه‌هایی برای مدیریت APIها قرار داده شده است:
   - با فعال کردن گزینه **[مجوز معامله]**، فرد می‌تواند از طریق این API معامله انجام دهد.
   - با برداشتن تیک گزینه **[فعال]**، API غیرفعال می‌شود. 
- **محدودیت‌های دسترسی به IP:**  گزینه‌های این بخش نحوه اعمال محدودیت‌ در دسترسی به IP را مشخص می‌کند.
   -  گزینه **[بدون محدودیت]** اجازه دسترسی از هر آدرس IP را می‌دهد و امنیت کمتری دارد، بنابراین انتخاب آن توصیه نمی‌شود.
   -  با انتخاب گزینه **[دسترسی محدود فقط به IP های قابل اعتماد]** لازم است در فیلد پایین صفحه، IP که می‌تواند دسترسی داشته باشد را  وارد و **[تایید]** کنید. 
    
> **توجه** <br>
 به محدودیت‌های دسترسی IP توجه داشته باشید. توصیه می‌شود به دلایل امنیتی گزینه **[دسترسی محدود فقط به IP های قابل اعتماد
 ]** را انتخاب کنید.

**5.** در انتها برای ذخیره کردن تغییرات بر روی دکمه **[ذخیره]** کلیک کنید. 
