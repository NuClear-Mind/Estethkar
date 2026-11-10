# إستذكار / Estethkar

**شاشة عائمة صغيرة تعدّ الوقت للصلاة القادمة وتنبّهك عند الأذان والإقامة، حتى وأنت داخل اللعبة.**
**A small floating countdown for Windows that stays above your games and alerts you at adhan and iqama.**

<p align="center">
  <img src="docs/images/panel-prayer.png" alt="Countdown to the next prayer" width="48%">
  <img src="docs/images/panel-iqama.png" alt="Iqama countdown in gold" width="48%">
</p>

## ⬇️ تحميل / Download

**[تحميل المثبّت / Download the installer: Estethkar-Setup.exe](https://github.com/NuClear-Mind/estethkar-releases/releases/latest/download/Estethkar-Setup.exe)**

- ملف واحد. يختار لك مجلد ويضيف اختصار على سطح المكتب ويشغّل البرنامج.
  One file. It picks a folder, adds a desktop shortcut and starts the app.
- بدون تثبيت؟ حمّل `Estethkar.exe` من [صفحة الإصدارات](https://github.com/NuClear-Mind/estethkar-releases/releases/latest) وشغّله مباشرة.
  No installer? Download `Estethkar.exe` from the [releases page](https://github.com/NuClear-Mind/estethkar-releases/releases/latest) and run it.
- يحتاج Windows 10 أو 11.
  Requires Windows 10 or 11.

## ✨ المميزات / Features

- **عدّاد فوق الألعاب:** كبسولة أفقية أو عمودية أو لوحة كاملة، بحجم من 50٪ إلى 250٪، وتحركها بالماوس. اختصار **Shift + Alt + P** يظهرها ويخفيها.
  **Counter over your games:** horizontal or vertical capsule, or a full panel, 50% to 250% in size, movable with the mouse. **Shift + Alt + P** shows or hides it.
- **تمييز الإقامة:** عدّاد الإقامة يظهر بلون ذهبي ويحمل كلمة «الإقامة»، فما تلتبس عليك مع الأذان.
  **Iqama stands out:** the iqama countdown is gold and labelled, so it is never mistaken for the adhan.
- **تنبيه بدون إزعاج:** النقطة تومض قبل الأذان بـ 3 ثواني وقبل الإقامة بـ 5 ثواني، بدون صوت.
  **Quiet heads-up:** the dot blinks 3 seconds before adhan and 5 seconds before iqama, silently.
- **إشعار وصوت دائمًا:** شريط من أعلى الشاشة أو بطاقة في الزاوية، مع أربعة أصوات جاهزة أو ملف WAV خاص. يشتغلان حتى لو كانت لعبة تعمل.
  **Alert and sound, always:** a banner at the top or a card in a corner, with four built-in sounds or your own WAV file. They work while a game is running.
- **مواقيت دقيقة بدون إنترنت:** تُحسب على جهازك حسب مدينتك بطريقة أم القرى، وتقدر تضبط كل صلاة بالثواني لتطابق مسجدك.
  **Accurate times, offline:** calculated on your PC for your city (Umm al-Qura), and you can shift each prayer by seconds to match your mosque.
- **عربي وإنجليزي**، والمدن قابلة للبحث بالعربي والإنجليزي.
  **Arabic and English**, with cities searchable in both.
- **يشتغل مع ويندوز** ويتحدّث من داخل البرنامج بضغطة زر، ويُحذف بالكامل من الإعدادات.
  **Starts with Windows**, updates itself from inside the app with one click, and uninstalls completely from the settings.

<p align="center">
  <img src="docs/images/alert.png" alt="Alert banner" width="60%">
</p>

<p align="center">
  <img src="docs/images/settings-ar.png" alt="الإعدادات" width="48%">
  <img src="docs/images/settings-en.png" alt="Settings" width="48%">
</p>

## 🎮 الألعاب / Games

- الشاشة والإشعار يظهران فوق الألعاب في وضع **Borderless** أو **Windowed Fullscreen**.
  The panel and alerts show above games in **Borderless** or **Windowed Fullscreen** mode.
- وضع **Exclusive Fullscreen** الحقيقي يخفي أي نافذة فوقه، وهذا من ويندوز. الصوت يشتغل لكن الشاشة ما تظهر. غيّر وضع اللعبة إلى Borderless.
  True **Exclusive Fullscreen** hides every window above it, which is a Windows limit. The sound still plays but nothing shows. Switch the game to Borderless.
- البرنامج **لا يتدخل في اللعبة**: لا حقن ولا قراءة ذاكرة ولا هوكات. يستخدم نافذة عادية وطلبات ويندوز القياسية فقط. مع ذلك ما أقدر أضمن كيف يتعامل كل نظام مكافحة غش مع أي نافذة عائمة، فالألعاب التنافسية الحساسة جرّبه فيها بحذر.
  The app **never touches the game**: no injection, no memory reading, no hooks. It uses a normal window and standard Windows calls only. Still, I cannot promise how every anti-cheat treats any overlay window, so be careful in strict competitive games.

## 🔒 الخصوصية / Privacy

- لا حساب، ولا تتبّع، ولا إعلانات، ولا بيانات تُرسل عنك.
  No account, no tracking, no ads, nothing about you is sent anywhere.
- الإعدادات تُحفظ في ملف `config.json` جنب البرنامج على جهازك فقط.
  Settings are stored in a `config.json` next to the app, on your PC only.
- الاتصالات بالإنترنت محدودة بشيئين:
  The only network connections are:
  1. التحقق من التحديث من GitHub (يمكن إيقافه من الإعدادات).
     Checking GitHub for updates (can be turned off in Settings).
  2. تحديد المدينة من الـ IP عبر `ipapi.co`، فقط إذا اخترت «تلقائي». الافتراضي هو اختيار المدينة يدويًا.
     Detecting your city from your IP through `ipapi.co`, only if you choose "automatic". The default is picking the city yourself.

## 🛡️ تحذير ويندوز / Windows warning

البرنامج جديد وغير موقّع رقميًا، فقد يعرض ويندوز **SmartScreen** أو يعلّمه مضاد الفيروسات خطأ. هذا يحصل مع البرامج الصغيرة غير الموقّعة.
The app is new and not code-signed, so Windows **SmartScreen** may warn, or an antivirus may flag it by mistake. This happens with small unsigned apps.

- اضغط **More info** ثم **Run anyway**.
  Click **More info**, then **Run anyway**.
- تقدر تتأكد أن الملف سليم: بصمة **SHA-256** لكل ملف مكتوبة في ملاحظات كل إصدار. في PowerShell: `Get-FileHash .\Estethkar-Setup.exe`
  You can verify the file: the **SHA-256** of each file is in the release notes. In PowerShell: `Get-FileHash .\Estethkar-Setup.exe`

## 🕌 عن المواقيت / About the times

- الطريقة: **أم القرى** (الفجر 18.5°، العشاء بعد المغرب بـ 90 دقيقة و 120 في رمضان). قورنت النتائج مع خدمة Aladhan.
  Method: **Umm al-Qura** (Fajr 18.5°, Isha 90 minutes after Maghrib, 120 in Ramadan). Results were compared against the Aladhan service.
- المواقيت تعتمد على ساعة ويندوز ومنطقتها الزمنية، فخلّ مزامنة الوقت مفعّلة.
  Times depend on the Windows clock and time zone, so keep time sync on.
- الجدول الرسمي لمسجدك أو مدينتك هو المرجع. استخدم ضبط الثواني في الإعدادات إن اختلف.
  Your mosque's or city's official timetable is the authority. Use the per-prayer adjustment if it differs.

## 🗑️ الحذف / Uninstall

الإعدادات ← عام ← **إلغاء تثبيت إستذكار**، أو من إعدادات ويندوز ← التطبيقات. يحذف البرنامج وملفاته والاختصار وتشغيله مع ويندوز.
Settings → General → **Uninstall Estethkar**, or Windows Settings → Apps. It removes the app, its files, the shortcut and the start-with-Windows entry.

## 🐞 مشكلة أو اقتراح / Problems and ideas

افتح [Issue](https://github.com/NuClear-Mind/estethkar-releases/issues/new/choose) واكتب رقم الإصدار واسم اللعبة ووضع الشاشة فيها.
Open an [issue](https://github.com/NuClear-Mind/estethkar-releases/issues/new/choose) with the version, the game and its display mode.

سجل التغييرات / Changelog: [CHANGELOG.md](CHANGELOG.md)

## 📄 الرخصة والشكر / License and credits

MIT. Copyright (c) 2026 Turky ALrowaily. See [LICENSE](LICENSE).

بيانات المدن من [GeoNames](https://www.geonames.org/) (المدن التي عدد سكانها 15,000 أو أكثر)، بترخيص [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
City data comes from [GeoNames](https://www.geonames.org/) (cities with 15,000 people or more), licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
