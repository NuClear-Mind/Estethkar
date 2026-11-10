# سجل التغييرات / Changelog

## 1.0.13
- إصلاح تعطل البرنامج بعد التحديث من داخل البرنامج ("DLL load failed while importing QtWidgets").
  Fixed the crash right after an in-app update ("DLL load failed while importing QtWidgets").

## 1.0.12
- تنبيه الأذان والإقامة (الإشعار والصوت) يشتغل دائمًا حتى لو كانت لعبة تعمل. أُزيل خيار الكتم.
  Adhan and iqama alerts (pop-up and sound) always work while a game is running. The mute option was removed.
- أُزيلت صفحة الترحيب. أول مرة يومض إطار أصفر حول «التشغيل مع ويندوز» في الإعدادات، ويظهر شريط تنبيه إذا كان مطفيًا.
  The welcome dialog is gone. On first launch a yellow frame blinks around "Start with Windows" in Settings, and a banner shows while it is off.

## 1.0.11
- عدّاد الإقامة بلون ذهبي مع كلمة «الإقامة»، ليتميز عن عدّاد الأذان.
  The iqama countdown is gold and labelled, so it stands out from the adhan countdown.

## 1.0.10
- تحديث أوثق: استبدال الملف بخطوة واحدة مع ملف `update.log` لتتبع أي مشكلة.
  More reliable update: the exe is swapped in one step, with an `update.log` to trace any problem.

## 1.0.9
- أُزيل زر التحديث من الشاشة العائمة. النقطة تومض قبل الأذان بـ 3 ثواني وقبل الإقامة بـ 5 ثواني بدون صوت.
  Removed the update button from the floating panel. The dot blinks 3 seconds before adhan and 5 before iqama, silently.

## 1.0.8
- علامة موافقة ويندوز على التشغيل مع ويندوز، واسم نظيف في قائمة بدء التشغيل.
  Windows startup approval flag, and a clean name in the startup list.

## 1.0.7
- حذف كامل عند إلغاء التثبيت، وعلامة صح على الخيارات المفعّلة.
  Full uninstall, and a tick on checked boxes.

## 1.0.6
- لا يتعطل البرنامج إذا كانت بيانات المنطقة الزمنية ناقصة.
  No crash when time zone data is missing.

## 1.0.5
- نسخة واحدة فقط تعمل، علامة ✓ عند آخر إصدار، واختصار سطح المكتب من المثبّت.
  Only one copy runs at a time, a ✓ when up to date, and a desktop shortcut from the installer.

## 1.0.4
- برنامج إلغاء تثبيت منفصل جنب البرنامج، ومثبّت بملف واحد.
  A separate uninstaller next to the app, and a one-file installer.

## 1.0.0 – 1.0.3
- الإصدار الأول: عدّاد عائم، تنبيهات الأذان والإقامة، مواقيت أم القرى، عربي وإنجليزي، والتحديث من داخل البرنامج، والاسم إستذكار.
  First releases: floating countdown, adhan and iqama alerts, Umm al-Qura times, Arabic and English, in-app update, and the name Estethkar.
