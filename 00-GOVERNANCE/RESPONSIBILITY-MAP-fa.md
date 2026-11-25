# نقشهٔ مسئولیت — NU-Driver-General-Package

**وضعیت نقش:** دستور مستقیم مالک؛ این مخزن محل انتشار نسخه‌های نهایی عمومی و دانلود کاربران است.

## مسئولیت اصلی

- دریافت artifact نهایی از مخزن خصوصی بسته‌بندی.
- ارائهٔ Releaseهای نسخه‌دار و فایل‌های دانلودی کاربران.
- انتشار manifest، checksum، راهنمای نصب/استفاده/ارتقا و ماتریس سازگاری.
- نگهداری changelog و تاریخچهٔ نسخه‌های عمومی.
- حفظ ردیابی کامل به source commit و بستهٔ خصوصی.

## ورودی مجاز

فقط artifactی که در [N.U-Driver-Private-Packaging](https://github.com/mobinabinshun-beep/N.U-Driver-Private-Packaging) جمع‌آوری و به وضعیت RELEASE-READY رسیده، hash آن بررسی شده، مجوزهای انتشارش روشن است و دستور انتشار لازم برای همان نسخه ثبت شده است.

## خارج از دامنه

- جمع‌آوری candidateهای ناقص یا ساخت روزمره.
- source code اصلی Driver.
- بسته‌های داخلی، فایل‌های محرمانه، secretها، tokenها و کلیدهای خصوصی.
- انتشار خودکار یا اعلام نسخهٔ رسمی بدون gateهای لازم.

## زنجیرهٔ منبع

- منبع Native فعلی: https://github.com/mobinabinshun-beep/mobinabinshun-beep/tree/feat/nu-native-runtime-gen1-foundation
- PR کاندید: https://github.com/mobinabinshun-beep/mobinabinshun-beep/pull/195
- مخزن staging خصوصی: https://github.com/mobinabinshun-beep/N.U-Driver-Private-Packaging
- نقشهٔ شبکه: https://github.com/mobinabinshun-beep/Documentation/blob/docs/network-integration-2026-11-25/00-START-HERE/REPOSITORY-NETWORK-INDEX-fa.md

## Gate انتشار

1. بستهٔ نهایی از مخزن خصوصی دریافت شود.
2. SHA-256 با مقدار ثبت‌شده در بستهٔ خصوصی تطبیق کند.
3. manifest، نسخه، platform، dependency و مجوزها تأیید شوند.
4. تست‌های لازم، محدودیت‌ها و وضعیت QA مستند باشند.
5. تأیید/دستور انتشار لازم برای همان نسخه ثبت شده باشد.
6. GitHub Release و فایل دانلودی با checksum و راهنمای روشن ایجاد شوند.

## وضعیت فعلی

مخزن هنوز artifact یا Release عمومی ندارد. این به معنی آماده‌بودن Driver برای دانلود نیست؛ Native Runtime فعلی هنوز کاندید توسعه است و باید ابتدا در مخزن خصوصی آماده شود.
