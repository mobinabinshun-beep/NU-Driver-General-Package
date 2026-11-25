# N.U Driver — General Package

<badge>PUBLIC DOWNLOADS</badge>

این مخزن محل **انتشار عمومی نسخه‌های نهایی N.U Driver برای دانلود و استفادهٔ کاربران** است. اینجا مقصد بسته‌هایی است که در مخزن خصوصی جمع‌آوری، تکمیل، بررسی و برای انتشار آماده شده‌اند.

## مسیر دریافت بسته

1. منبع کد در مخزن تولیدکنندهٔ مربوطه توسعه و آزموده می‌شود.
2. بسته در [N.U-Driver-Private-Packaging](https://github.com/mobinabinshun-beep/N.U-Driver-Private-Packaging) جمع‌آوری و آمادهٔ انتشار می‌شود.
3. پس از تکمیل بررسی‌ها و ثبت مجوز/دستور انتشار، همان artifact نهایی به این مخزن منتقل می‌شود.
4. کاربران نسخهٔ عمومی را از بخش GitHub Releases و فایل‌های دانلودی همان نسخه دریافت می‌کنند.

## چه چیزی اینجا منتشر می‌شود؟

- فقط بستهٔ نهایی و مجاز برای انتشار عمومی.
- فایل Release قابل دانلود، نسخه و manifest عمومی.
- SHA-256/checksum و راهنمای بررسی فایل دانلودی.
- راهنمای نصب، استفاده، ارتقا، حذف و ماتریس سازگاری.
- نمونه‌های عمومی و غیرمحرمانه.

## چه چیزی اینجا قرار نمی‌گیرد؟

- کاندیدهای ناقص یا در حال آزمون خصوصی.
- سورس یا artifact محدودشده، دادهٔ داخلی و تنظیمات محرمانه.
- secret، token، credential یا کلید خصوصی امضا.
- بسته‌ای که منبع، مجوز، hash یا وضعیت آزمون آن روشن نیست.

## پیوندهای سامانه

- [نقشهٔ شبکهٔ مخازن Game Studio](https://github.com/mobinabinshun-beep/Documentation/blob/docs/network-integration-2026-11-25/00-START-HERE/REPOSITORY-NETWORK-INDEX-fa.md)
- [مخزن خصوصی آماده‌سازی بسته‌ها](https://github.com/mobinabinshun-beep/N.U-Driver-Private-Packaging)
- [مخزن اصلی Game Studio و منبع فعلی Native Runtime](https://github.com/mobinabinshun-beep/mobinabinshun-beep)
- [شاخهٔ Native Runtime Gen 1](https://github.com/mobinabinshun-beep/mobinabinshun-beep/tree/feat/nu-native-runtime-gen1-foundation)
- [PR #195 — Native Runtime Gen 1](https://github.com/mobinabinshun-beep/mobinabinshun-beep/pull/195)
- [Documentation](https://github.com/mobinabinshun-beep/Documentation)
- [Manual QA](https://github.com/mobinabinshun-beep/Manual-Testing-and-Reporting-Log)
- [Protocols](https://github.com/mobinabinshun-beep/Repository-of-protocols-principles-norms-manifestos-and-rules-for-the-Game-N.U-Studio-project.)

## وضعیت فعلی

این مخزن هنوز Release یا artifact عمومی ندارد. وجود این مخزن به معنی آماده‌بودن Driver برای دانلود نیست. Native Runtime Gen 1 در مخزن محصول یک کاندید توسعه است و هنوز gateهای لازم برای انتشار را نگذرانده است. اولین انتشار فقط پس از انتقال یک artifact نهایی و راستی‌آزمایی‌شده از مخزن خصوصی انجام می‌شود.

## سیاست انتشار

- [دروازهٔ پذیرش و انتشار عمومی](01-SPECIFICATION/PUBLIC-RELEASE-ACCEPTANCE-fa.md)
- [نقشهٔ مسئولیت مخزن](00-GOVERNANCE/RESPONSIBILITY-MAP-fa.md)
- [تاریخچهٔ مخزن](00-GOVERNANCE/REPOSITORY-HISTORY-fa.md)
