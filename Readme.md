# 🚀 برنامج تحميل فيديوهات يوتيوب (YoutubeDownloader)

[![Status](https://img.shields.io/badge/status-maintenance-ffd700.svg)](https://github.com/Tyrrrz/.github/blob/master/docs/project-status.md)
[![Made in Ukraine](https://img.shields.io/badge/made_in-ukraine-ffd700.svg?labelColor=0057b7)](https://tyrrrz.me/ukraine)
[![Build](https://img.shields.io/github/actions/workflow/status/Tyrrrz/YoutubeDownloader/main.yml?branch=master)](https://github.com/Tyrrrz/YoutubeDownloader/actions)
[![Release](https://img.shields.io/github/release/Tyrrrz/YoutubeDownloader.svg)](https://github.com/Tyrrrz/YoutubeDownloader/releases)
[![Downloads](https://img.shields.io/github/downloads/Tyrrrz/YoutubeDownloader/total.svg)](https://img.shields.io/github/downloads/Tyrrrz/YoutubeDownloader/total.svg)
[![Discord](https://img.shields.io/discord/869237470565392384?label=discord)](https://discord.gg/2SUWKFnHSm)
[![Fuck Russia](https://img.shields.io/badge/fuck-russia-e4181c.svg?labelColor=000000)](https://twitter.com/tyrrrz/status/1495972128977571848)

<p align="center">
    <img src="favicon.png" alt="Icon" />
</p>

**YoutubeDownloader** هو بوابتك لتحميل ومشاركة المحتوى المفضل لديك من يوتيوب بسهولة ومرونة. سواء كنت تريد حفظ فيديو فردي، قائمة تشغيل كاملة، أو محتوى قناة بأكمله، يوفر لك التطبيق واجهة رسومية بسيطة لتبدأ فوراً.

> **ملاحظة فنية**: يعتمد هذا التطبيق على مكتبة [**YoutubeExplode**](https://github.com/Tyrrrz/YoutubeExplode) للتفاعل مع خوادم يوتيوب بفعالية.
<br>

---

## 🌟 الميزات الرئيسية والإبداعية

صُمم **YoutubeDownloader** ليمنحك تحكماً كاملاً في تجربة التنزيل:

* **متعدد المنصات (Cross-platform)**: واجهة رسومية متطورة تعمل على أنظمة تشغيل متعددة.
* **مرونة التنزيل**: تحميل الفيديوهات عبر **الروابط المباشرة** (فيديو فردي، قائمة تشغيل، قناة).
* **البحث السريع**: إمكانية البحث عن الفيديوهات بواسطة الكلمات المفتاحية دون الحاجة لمغادرة التطبيق.
* **تحكم كامل بالجودة**: اختر صيغة الفيديو والجودة المناسبة لك (MP4، WebM، إلخ).
* **تضمين المحتوى الإضافي تلقائياً**:
    * **🎧 الصوتيات**: تضمين مسارات صوتية بديلة اللغات.
    * **📝 الترجمة**: تضمين ملفات الترجمة (Subtitles) في الفيديو.
    * **🏷️ الوسوم**: حقن وسوم الميديا (Media Tags) تلقائياً لتنظيم مكتبتك.
* **محتوى خاص**: دعم تسجيل الدخول بحساب يوتيوب للوصول إلى المحتوى الخاص والمحمي.

---

## ⬇️ التحميل والتنصيب

ابدأ باستخدام التطبيق في خطوات بسيطة:

| الإصدار | الرابط | الوصف |
| :--- | :--- | :--- |
| **الإصدار المستقر (المُوصى به)** | 🟢 [**أحدث إصدار**](https://github.com/Tyrrrz/YoutubeDownloader/releases/latest) | الإصدار الأكثر استقراراً وجاهزية للاستخدام اليومي. |
| **إصدار CI (للمطورين)** | 🟠 [بناء التكامل المستمر](https://github.com/Tyrrrz/YoutubeDownloader/actions/workflows/main.yml) | أحدث بناء تجريبي يحتوي على الميزات الأخيرة. |

> **تنويه هام لـ MacOS**:
> قد تحتاج إلى إزالة ملف التطبيق من الحجر الصحي (Quarantine) قبل تشغيله. يمكنك فعل ذلك عبر تشغيل الأمر التالي في الطرفية (Terminal) بعد التنزيل:
> `xattr -rd com.apple.quarantine YoutubeDownloader.app`

> **ملاحظة حول FFmpeg**:
> يأتي **YoutubeDownloader** مُرفقاً بأداة [FFmpeg](https://ffmpeg.org) لمعالجة ودمج الفيديوهات. إذا كنت تفضل استخدام تثبيتك الخاص من FFmpeg، يمكنك تنزيل النسخة الخالية منه (`YoutubeDownloader.Bare.*`).

---

## 🖼️ لمحات من التطبيق (Screenshots)

شاهد كيف يبدو التطبيق في العمل:

| عرض قائمة تشغيل | تنزيل فيديو واحد | إدارة تنزيلات متعددة |
| :---: | :---: | :---: |
| ![list](.assets/list.png) | ![single](.assets/single.png) | ![multiple](.assets/multiple.png) |

---

## 💖 دعم المشروع والمساهمة

**يعتمد تطوير هذا المشروع بالكامل على دعم المجتمع.** إذا وجدت التطبيق مفيداً، نرجو أن تفكر في التبرع لدعم استمرار تطويره وصيانته:

<a href="https://tyrrrz.me/donate" target="_blank">
    <img src="https://img.shields.io/badge/Donate-Support%20Development-blue.svg?style=for-the-badge&logo=paypal" alt="تبرع لدعم المشروع" />
</a>

---

## شروط الاستخدام والقضايا السياسية 🇺🇦<sup>[[?]](https://github.com/Tyrrrz/.github/blob/master/docs/why-so-political.md)</sup>

باستخدامك لهذا المشروع أو رمز مصدره، بأي شكل أو غرض، فإنك تمنح **موافقتك الضمنية** على البيانات التالية:

-   أنت **تدين روسيا وعدوانها العسكري على أوكرانيا**.
-   أنت **تدرك أن روسيا قوة احتلال غزت دولة ذات سيادة بشكل غير قانوني**.
-   أنت **تدعم وحدة أراضي أوكرانيا**، بما في ذلك مطالبتها بأراضي القرم ودونباس المحتلة مؤقتاً.
-   أنت **ترفض الروايات الكاذبة** التي تروج لها الدعاية الروسية الرسمية.

لمعرفة المزيد عن الحرب وكيف يمكنك المساعدة، [اضغط هنا](https://tyrrrz.me/ukraine). المجد لأوكرانيا! 🇺🇦
