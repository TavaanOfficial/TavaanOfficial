<div dir="rtl" lang="fa">

<div align="center">

# Github.md — مشخصات انتشار مخزن رسمی تَوان

### مرجع داخلی راه‌اندازی و انتشار مخزن معرفی رسمی پروژهٔ تَوان

</div>

> **یادداشت:** این فایل سند داخلی انتشار است و برای مخزن عمومی استاندارد نیست. اگر این فایل را در مخزن عمومی نگه‌دارید، می‌توانید آن را به `docs/PUBLISHING.md` منتقل کنید یا فقط برای تیم نگه‌داری کنید.

---

## ۱. عنوان کامیت (Commit Title)

عنوان کامیت بر اساس قرارداد Conventional Commits و به زبان فارسی (همسو با ماهیت «فارسی در مرکز» پروژه) نوشته می‌شود:

```
feat: راه‌اندازی مخزن معرفی رسمی تَوان با فایل‌های همراه یکپارچه
```

> **نکته:** در صورت ترجیح انگلیسی، عنوان جایگزین:
> ```
> feat: bootstrap official Tavaan intro repository with integrated companion files
> ```

---

## ۲. توضیحات کامیت (Commit Description)

متن کامل پیام کامیت:

```text
feat: راه‌اندازی مخزن معرفی رسمی تَوان با فایل‌های همراه یکپارچه

این کامیت، مخزن معرفی رسمی پروژهٔ تَوان را راه‌اندازی می‌کند و
مجموعه‌ای از فایل‌های همراه را به‌صورت یکپارچه ارائه می‌دهد.

تَوان یک فریمورک (چارچوب نرم‌افزاری) PHP بدون وابستگی بیرونی در زمان اجرا و با رویکرد
«فارسی در مرکز» است که برای توانمندسازی توسعه‌دهندهٔ فارسی‌زبان
ساخته شده است.

فهرست فایل‌های افزوده‌شده:
- README.md: معرفی کامل پروژه (نام استاندارد)
- LICENSE: متن کامل پروانهٔ MIT (بدون پسوند، سال ۲۰۲۶)
- LICENSE.fa.md: ترجمهٔ فارسی غیررسمی پروانه
- SECURITY.md: سیاست امنیتی با GitHub Security Advisories
- CONTRIBUTING.md: راهنمای مشارکت با CLA و سیاست زبان commit واحد
- CODE_OF_CONDUCT.md: منشور رفتاری با فرایند تجدیدنظر
- LICENSING.md: راهبرد کامل مجوزدهی چندمخزنی (AGPL، Apache 2.0، MIT، تجاری)
- CLA.md: توافقنامهٔ مجوزدهی مشارکت‌کننده
- GOVERNANCE.md: سند حاکمیت
- .gitignore: الگوی PHP
- .github/ISSUE_TEMPLATE/: قالب‌های گزارش باگ و پیشنهاد ویژگی
- .github/PULL_REQUEST_TEMPLATE.md: قالب PR
- Github.md: این فایل (سند داخلی انتشار)

اصول نگارشی رعایت‌شده:
- معادل‌نویسی اصطلاحات کلیدی (بدون وابستگی در زمان اجرا، فارسی در مرکز،
  توانمندی بدون مرز و ...)
- اعمال راست‌چینی (RTL) با HTML بومی (dir="rtl")، بدون اتکا به CSS سفارشی
- رعایت گرامر فارسی، نیم‌فاصله‌ها و کاراکترهای فارسی
- عدم اشاره به جزئیاتی که در طول زمان تغییر می‌کنند (تعداد موتور،
  کیت، ماژول، فاز، نسخهٔ پایدار و ...)
- ارجاع به مخازن رسمی در مسیر github.com/TavaanOfficial
- حذف ایمیل‌های «به‌زودی» و استفاده از GitHub Security Advisories
- افزودن CLA از اولین commit برای امکان دوگانه‌مجوزدهی

راهبرد مجوزدهی به تفکیک مخازن:
- TavaanOfficial (این مخزن): MIT
- Tavaan-Framework (هسته): AGPLv3
- Tavaan-Contracts (قراردادها): Apache 2.0
- Tavaan-SDK (ابزار): MIT
- Tavaan-Docs (مستندات): CC BY-SA 4.0
- موتورهای سازمانی: تجاری (مخزن خصوصی)

جزئیات راهبرد مجوزدهی در LICENSING.md آمده است.
```

---

## ۳. خلاصهٔ معرفی مخزن (Repository About / Description)

### گزینهٔ اصلی (فارسی)

```
فریمورک PHP 8.2+ بدون وابستگی بیرونی در زمان اجرا و با رویکرد «فارسی در مرکز» — برای توانمندسازی توسعه‌دهندهٔ فارسی‌زبان در ساخت سامانه‌های بزرگ و روشن. شعار: توانمندی بدون مرز.
```

### گزینهٔ جایگزین (انگلیسی)

```
Zero-runtime-dependency, Persian-first PHP 8.2+ framework — empowering the Persian-speaking community to build large, transparent systems. Slogan: Infinite Capability.
```

### گزینهٔ بسیار کوتاه (نمایش در کارت مخزن)

```
فریمورک PHP 8.2+ بدون وابستگی در زمان اجرا و با رویکرد «فارسی در مرکز».
```

---

## ۴. سایر موارد الزامی

### ۴.۱ مسیر راهنمای پروفایل سازمان

GitHub برای نمایش راهنما در صفحهٔ سازمان، از قرارداد استاندارد `.github/profile/README.md` استفاده می‌کند. مخزن هم‌نام سازمان (`TavaanOfficial/TavaanOfficial`) به‌تنهایی تضمین‌کنندهٔ نمایش در پروفایل سازمان نیست.

**دو گزینهٔ پیشنهادی:**

<table dir="rtl">
  <thead>
    <tr>
      <th style="width: 25%;">گزینه</th>
      <th style="width: 75%;">ساختار</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><strong>الف — پروفایل سازمان</strong></td><td>مخزن <span dir="ltr">.github</span>; راهنما در <span dir="ltr">`profile/README.md`</span>; فایل‌های <span dir="ltr">SECURITY.md</span>، <span dir="ltr">CONTRIBUTING.md</span> و <span dir="ltr">CODE_OF_CONDUCT.md</span> در ریشه به‌عنوان فایل‌های پیش‌فرض سازمان.</td></tr>
    <tr><td><strong>ب — مخزن معرفی عادی</strong></td><td>مخزن <span dir="ltr">TavaanOfficial</span>; راهنما در ریشه با نام <span dir="ltr">`README.md`</span>; این مخزن پروفایل سازمان را خودکار نمایش نمی‌دهد.</td></tr>
  </tbody>
</table>

> **توصیه:** گزینهٔ الف را انتخاب کنید و فایل‌ها را مطابق آن ساماندهی کنید. در این حالت، همهٔ لینک‌های نسبی در فایل‌ها باید با ساختار `profile/README.md` هماهنگ شوند.

### ۴.۲ نوع مخزن (Repository Type)

- **نوع دسترس‌پذیری:** `Public` (عمومی)
- **شاخهٔ پیش‌فرض:** `main`
- **راه‌اندازی با:** `README.md`، `LICENSE`، `.gitignore` (الگوی PHP)، `SECURITY.md`، `CONTRIBUTING.md`، `CODE_OF_CONDUCT.md`

### ۴.۳ برچسب‌ها / Topics

برچسب‌های پیشنهادی برای فیلد Topics مخزن:

```
php              php-framework          zero-runtime-dependencies
php82            framework              persian
persian-first    jalali                 modular-monolith
hmvc             event-driven           hexagonal-architecture
domain-driven    enterprise             erp
bpms             workflow-engine         multi-tenancy
self-contained   contract-first         event-sourcing
cqrs             outbox-pattern         open-source
```

> **یادداشت:** `zero-dependency` به `zero-runtime-dependencies` تغییر یافت تا دقیق‌تر باشد.

### ۴.۴ پروانه (License)

- **نوع:** پروانهٔ MIT
- **فایل:** `LICENSE` (بدون پسوند) در ریشهٔ مخزن
- **سال حق مؤلف:** ۲۰۲۶
- **دارنده:** `Tavaan Project and contributors`
- **ترجمهٔ فارسی:** در فایل جداگانهٔ `LICENSE.fa.md` با یادداشت «متن انگلیسی مرجع است»

> **یادداشت دامنهٔ پروانه:** این پروانهٔ MIT فقط برای محتوای همین مخزن معرفی اعمال می‌شود. پروانهٔ مخازن دیگر (مثل `Tavaan-Framework` تحت AGPL) در همان مخزن اعلام می‌شود. برای راهبرد کامل، فایل `LICENSING.md` را ببینید.

### ۴.۵ فایل‌های همراه یکپارچه

<table dir="rtl">
  <thead>
    <tr>
      <th style="width: 28%;">فایل</th>
      <th style="width: 55%;">کاربرد</th>
      <th style="width: 17%;">وضعیت</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><span dir="ltr">README.md</span></td><td>معرفی کامل پروژه با ساختار راست‌چین (نام استاندارد)</td><td>✅ شامل</td></tr>
    <tr><td><span dir="ltr">Github.md</span></td><td>این فایل (سند داخلی انتشار)</td><td>✅ شامل</td></tr>
    <tr><td><span dir="ltr">LICENSE</span></td><td>متن کامل پروانهٔ MIT (بدون پسوند، سال ۲۰۲۶)</td><td>✅ شامل</td></tr>
    <tr><td><span dir="ltr">LICENSE.fa.md</span></td><td>ترجمهٔ فارسی غیررسمی پروانه</td><td>✅ شامل</td></tr>
    <tr><td><span dir="ltr">LICENSING.md</span></td><td>راهبرد کامل مجوزدهی چندمخزنی</td><td>✅ شامل</td></tr>
    <tr><td><span dir="ltr">CLA.md</span></td><td>توافقنامهٔ مجوزدهی مشارکت‌کننده</td><td>✅ شامل</td></tr>
    <tr><td><span dir="ltr">GOVERNANCE.md</span></td><td>سند حاکمیت</td><td>✅ شامل</td></tr>
    <tr><td><span dir="ltr">SECURITY.md</span></td><td>سیاست امنیتی با GitHub Security Advisories</td><td>✅ شامل</td></tr>
    <tr><td><span dir="ltr">CONTRIBUTING.md</span></td><td>راهنمای مشارکت با CLA و سیاست زبان commit واحد</td><td>✅ شامل</td></tr>
    <tr><td><span dir="ltr">CODE_OF_CONDUCT.md</span></td><td>منشور رفتاری با فرایند تجدیدنظر</td><td>✅ شامل</td></tr>
    <tr><td><span dir="ltr">.gitignore</span></td><td>الگوی PHP</td><td>✅ شامل</td></tr>
    <tr><td><span dir="ltr">.github/ISSUE_TEMPLATE/</span></td><td>قالب‌های گزارش باگ و پیشنهاد ویژگی</td><td>✅ شامل</td></tr>
    <tr><td><span dir="ltr">.github/PULL_REQUEST_TEMPLATE.md</span></td><td>قالب PR</td><td>✅ شامل</td></tr>
  </tbody>
</table>

### ۴.۶ وب‌سایت / Homepage

- **آدرس وب‌سایت:** در دست راه‌اندازی
- **توصیه:** تا فعال‌شدن، فیلد Homepage را خالی نگه دارید. لینک‌های 404 به وب‌سایت هنوز‌ناموجود، اولین برداشت را خراب می‌کند.

### ۴.۷ کانال‌های رسمی پروژه

<table dir="rtl">
  <thead>
    <tr>
      <th style="width: 22%;">کانال</th>
      <th style="width: 58%;">آدرس</th>
      <th style="width: 20%;">وضعیت</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Issues همین مخزن</td><td><span dir="ltr">github.com/TavaanOfficial</span> → <span dir="ltr">Issues</span></td><td>✅ فعال</td></tr>
    <tr><td>Discussions</td><td><span dir="ltr">github.com/TavaanOfficial</span> → <span dir="ltr">Discussions</span></td><td>✅ فعال</td></tr>
    <tr><td>گزارش امنیتی</td><td><span dir="ltr">GitHub Security Advisories</span></td><td>✅ فعال</td></tr>
    <tr><td>وب‌سایت رسمی</td><td><span dir="ltr">tavaan.dev</span></td><td>🚧 در دست راه‌اندازی (بدون لینک تا فعال‌شدن)</td></tr>
    <tr><td>مخزن قراردادها</td><td><span dir="ltr">github.com/TavaanOfficial/Tavaan-Contracts</span></td><td>🚧 در دست راه‌اندازی</td></tr>
    <tr><td>مخزن پیاده‌سازی</td><td><span dir="ltr">github.com/TavaanOfficial/Tavaan-Framework</span></td><td>🚧 در دست راه‌اندازی</td></tr>
    <tr><td>مخزن SDK</td><td><span dir="ltr">github.com/TavaanOfficial/Tavaan-SDK</span></td><td>🚧 در دست راه‌اندازی</td></tr>
    <tr><td>مخزن مستندات</td><td><span dir="ltr">github.com/TavaanOfficial/Tavaan-Docs</span></td><td>🚧 در دست راه‌اندازی</td></tr>
    <tr><td>ایمیل رسمی</td><td>پس از راه‌اندازی دامنهٔ <span dir="ltr">tavaan.dev</span></td><td>🚧 در دست راه‌اندازی</td></tr>
  </tbody>
</table>

> **سیاست لینک:** تا فعال‌شدن واقعی یک کانال، آن را بدون لینک یا با برچسب «در دست راه‌اندازی» نمایش دهید. هیچ لینک 404 در مخزن نباید باشد.

### ۴.۸ مخازن هماهنگ در سازمان

تَوان در قالب چند مخزن، در سازمان رسمی GitHub نگهداری می‌شود:

<table dir="rtl">
  <thead>
    <tr>
      <th style="width: 22%;">مخزن</th>
      <th style="width: 33%;">نقش</th>
      <th style="width: 20%;">مجوز</th>
      <th style="width: 25%;">آدرس (پس از راه‌اندازی)</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><strong>TavaanOfficial</strong></td><td>معرفی رسمی و راهنمای سازمان</td><td><span dir="ltr">MIT</span></td><td><span dir="ltr">github.com/TavaanOfficial</span></td></tr>
    <tr><td><strong>Tavaan-Framework</strong></td><td>پیاده‌سازی مرجع فریمورک</td><td><span dir="ltr">AGPLv3</span></td><td><span dir="ltr">github.com/TavaanOfficial/Tavaan-Framework</span></td></tr>
    <tr><td><strong>Tavaan-Contracts</strong></td><td>قراردادها و <span dir="ltr">SPI</span></td><td><span dir="ltr">Apache 2.0</span></td><td><span dir="ltr">github.com/TavaanOfficial/Tavaan-Contracts</span></td></tr>
    <tr><td><strong>Tavaan-SDK</strong></td><td><span dir="ltr">SDK / CLI</span> و کتابخانهٔ کلاینت</td><td><span dir="ltr">MIT</span></td><td><span dir="ltr">github.com/TavaanOfficial/Tavaan-SDK</span></td></tr>
    <tr><td><strong>Tavaan-Docs</strong></td><td>مستندات تحلیلی-معماری</td><td><span dir="ltr">CC BY-SA 4.0</span></td><td><span dir="ltr">github.com/TavaanOfficial/Tavaan-Docs</span></td></tr>
    <tr><td>موتورهای سازمانی</td><td>قابلیت‌های تجاری</td><td>تجاری</td><td>مخزن خصوصی</td></tr>
  </tbody>
</table>

### ۴.۹ رویکرد نسخه‌گذاری و انتشار

- **مرجع:** SemVer
- **وضعیت:** پروژه در مرحلهٔ تکامل است؛ جزئیات پیاده‌سازی (تعداد موتورها، کیت‌ها، ماژول‌ها و فازبندی) در طول زمان افزایش یا کاهش خواهد یافت.
- **سیاست انتشار:** به‌جای وعده‌های زمان‌بندی‌شده و اعداد ثابت، در هر گام آنچه واقعاً آماده است منتشر می‌شود.

### ۴.۱۰ چک‌لیست راه‌اندازی مخزن

پیش از انتشار عمومی، موارد زیر را تأیید کنید:

<div dir="rtl">

- [ ] انتخاب ساختار `.github/profile/README.md` یا مخزن عادی با `README.md` و هماهنگ‌سازی همهٔ لینک‌ها
- [ ] نام فایل `README.md` است (نه `Readme.md`)
- [ ] وجود واقعی `LICENSE` (بدون پسوند) با MIT سال ۲۰۲۶ و دارندهٔ «Tavaan Project and contributors»
- [ ] وجود `LICENSE.fa.md` با ترجمهٔ فارسی
- [ ] وجود `.gitignore` مطابق الگوی PHP
- [ ] فعال بودن **GitHub Private Vulnerability Reporting** در تنظیمات مخزن
- [ ] وجود `SECURITY.md` با ارجاع به GitHub Security Advisories
- [ ] وجود `CONTRIBUTING.md` با CLA و سیاست زبان commit واحد
- [ ] وجود `CODE_OF_CONDUCT.md` با فرایند تجدیدنظر
- [ ] وجود `LICENSING.md` با راهبرد مجوزدهی چندمخزنی
- [ ] وجود `CLA.md` و `GOVERNANCE.md`
- [ ] وجود `.github/ISSUE_TEMPLATE/bug_report.yml` و `feature_request.yml`
- [ ] وجود `.github/PULL_REQUEST_TEMPLATE.md`
- [ ] فیلد About با خلاصهٔ فارسی پر شده
- [ ] Topics (با `zero-runtime-dependencies` به‌جای `zero-dependency`)
- [ ] **بدون لینک 404** به وب‌سایت، مخازن یا ایمیل
- [ ] شاخهٔ پیش‌فرض `main` است
- [ ] حفاظت شاخه (Branch protection) روی `main` فعال است
- [ ] CI برای `php -l`، PHPStan و آزمون‌ها فعال است
- [ ] تست رندر README در GitHub (حالت موبایل و دارک‌مود)
- [ ] روشن بودن مرز مجوز بین مخازن (طبق `LICENSING.md`)

</div>

### ۴.۱۱ الگوی .gitignore (فایل واقعی)

```gitignore
# Tavaan — .gitignore
/vendor/
/vendor-bin/
composer.lock

/storage/cache/
/storage/logs/
/storage/framework/
/storage/sessions/

.env
.env.local
.env.*.local
.phpstan.cache
.php-cs-fixer.cache
.phpunit.cache/

.vscode/
.idea/
*.swp
*.swo
.DS_Store
Thumbs.db

*.log
logs/
/build/
/dist/
*.tar
*.zip
*.gz

/coverage/
*.tmp
*.temp
*.bak
*.old
```

---

## ۵. خلاصهٔ معرفی پروژه (برای استفاده در توضیحات اجتماعی/متا)

> **تَوان (Tavaan)** فریمورک PHP با معماری ترکیبی و **بدون وابستگی بیرونی در زمان اجرا** است. نام آن از ریشهٔ فارسی «توان» به معنای توانمندسازی می‌آید و شعار آن «توانمندی بدون مرز» است. تَوان با رویکرد **مبتنی بر موتور** و **فارسی در مرکز**، پشتیبانی بومی از تقویم جلالی، ارقام فارسی و دادهٔ ایرانی را در سطح هسته ارائه می‌دهد و برای دامنه‌های بزرگ و مهاجرت تدریجی به میکروسرویس آماده است.

---

## ۶. اصول نگارشی رعایت‌شده در این بسته

<table dir="rtl">
  <thead>
    <tr>
      <th style="width: 28%;">اصل</th>
      <th style="width: 72%;">توضیح</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><strong>نام استاندارد</strong></td><td>استفاده از <span dir="ltr">README.md</span> (نه <span dir="ltr">Readme.md</span>) و <span dir="ltr">LICENSE</span> (بدون پسوند).</td></tr>
    <tr><td><strong>معادل‌نویسی اصطلاحات</strong></td><td>«بدون وابستگی در زمان اجرا»، «فارسی در مرکز»، «توانمندی بدون مرز».</td></tr>
    <tr><td><strong>بدون اتکا به CSS سفارشی</strong></td><td>استفاده از <span dir="ltr">`dir="rtl"`</span> بومی HTML و <span dir="ltr">`dir="ltr"`</span> برای متن‌های لاتین، بدون کلاس‌های CSS.</td></tr>
    <tr><td><strong>بدون لینک 404</strong></td><td>وب‌سایت، مخازن و ایمیل‌های ناموجود به‌صورت متن (بدون لینک) با برچسب «در دست راه‌اندازی».</td></tr>
    <tr><td><strong>CLA از روز اول</strong></td><td>امکان دوگانه‌مجوزدهی در آینده (AGPL + تجاری).</td></tr>
    <tr><td><strong>راهبرد مجوزدهی یکپارچه</strong></td><td>هر مخزن مجوز متناسب با نقش خود (AGPL، Apache 2.0، MIT، تجاری).</td></tr>
    <tr><td><strong>GitHub Security Advisories</strong></td><td>کانال امنیتی فعال از روز اول، بدون نیاز به ایمیل «به‌زودی».</td></tr>
    <tr><td><strong>برچسب وضعیت</strong></td><td>ویژگی‌ها و الگوهای امنیتی به‌عنوان «اهداف طراحی» معرفی شده‌اند.</td></tr>
    <tr><td><strong>گرامر فارسی</strong></td><td>اصلاح «میزانگری» به «تبعیض»، «کافهٔ اضافه» به «کسرهٔ اضافه»، «پوشانش داده» به «پوشاندن داده».</td></tr>
  </tbody>
</table>

---

<br />

<div align="center">

**تَوان | TavaanOfficial**
توانمندی بدون مرز

</div>

</div>
