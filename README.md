# NU Driver — General Package

> وضعیت این مخزن: **چارچوب اولیه برای بسته عمومی؛ هنوز محتوای اجرایی یا قرارداد API در آن ثبت نشده است.**

## مأموریت پیشنهادی
خانه بسته عمومی و قابل استفاده مجدد N.U Driver؛ شامل قراردادهای عمومی، راهنمای نصب و استفاده، نمونه‌های غیرمحرمانه، سازگاری نسخه‌ها و مستندات مصرف‌کنندگان.

## مسئولیت‌های پیشنهادی
- تعریف و مستندسازی سطح عمومی و پایدار Driver پس از شناسایی کد و مالک آن.
- نگهداری راهنمای نصب، پیکربندی عمومی، نمونه‌ها و ماتریس سازگاری.
- ثبت نسخه‌ها، تغییرات ناسازگار و راهنمای ارتقا.
- ارائه manifest و شواهد آزمون برای بسته‌های عمومی، در صورت ایجاد pipeline.

## خارج از دامنه
- داده‌ها، پیکربندی‌ها و artifactهای محرمانه.
- secretها، کلیدهای امضا و credentialها.
- بسته‌بندی خصوصی و استقرار داخلی؛ این حوزه به [N.U-Driver-Private-Packaging](https://github.com/mobinabinshun-beep/N.U-Driver-Private-Packaging) ارجاع می‌دهد.
- تصمیم‌گیری مستقل درباره قواعد کل سامانه؛ مرجع پروتکل‌ها [اینجاست](https://github.com/mobinabinshun-beep/Repository-of-protocols-principles-norms-manifestos-and-rules-for-the-Game-N.U-Studio-project.).

## ساختار پیشنهادی
- `00-GOVERNANCE/`: دامنه، مالکیت و تاریخچه
- `01-SPECIFICATION/`: قراردادها و مشخصات عمومی
- `02-PACKAGE/`: کد و اجزای قابل انتشار (پس از شناسایی منبع)
- `03-DOCUMENTATION/`: نصب، استفاده و ارتقا
- `04-EXAMPLES/`: نمونه‌های عمومی و غیرمحرمانه
- `05-TESTS/`: آزمون‌های خودکار و سازگاری

## پیوندهای سامانه
- [بسته‌بندی خصوصی](https://github.com/mobinabinshun-beep/N.U-Driver-Private-Packaging)
- [مخزن پروتکل‌ها](https://github.com/mobinabinshun-beep/Repository-of-protocols-principles-norms-manifestos-and-rules-for-the-Game-N.U-Studio-project.)
- [مستندات مرکزی](https://github.com/mobinabinshun-beep/Documentation)

## وضعیت فعلی شواهد
این مخزن هنگام ممیزی خالی بود: README، commit، branch محتوایی، کد، تست، workflow، issue، PR یا release قابل مشاهده نبود. این تغییر اولیه صرفاً ساختار مستنداتی ایجاد می‌کند و هیچ کد Driver را پیاده‌سازی یا منتقل نمی‌کند.

## حاکمیت
تعاریف این سند PROPOSED هستند. API یا قرارداد عمومی تا زمان شناسایی منبع واقعی Driver، مالک فنی و تصویب پروتکل مربوطه تثبیت‌شده محسوب نمی‌شود.
