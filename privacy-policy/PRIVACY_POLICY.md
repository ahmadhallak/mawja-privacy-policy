# سياسة الخصوصية لتطبيق «موجة» | Privacy Policy — Mawja - Arabic Radio & Podcast

- **اسم التطبيق (App Name):** موجة (`Mawja - Arabic Radio & Podcast`)
- **معرّف الحزمة (Package Name):** `com.volume.radio`
- **المطور والجهة المسؤولة (Developer / Data Controller):** `Novyra`
- **البريد الإلكتروني للتواصل وطلبات الخصوصية (Contact Email):** `apps.novyra@gmail.com`
- **تاريخ السريان وآخر تحديث (Effective & Last Updated Date):** 28 أكتوبر 2026 (October 28, 2026)

---

## القسم الأول: سياسة الخصوصية (باللغة العربية)

### 1. مقدمة
توضح سياسة الخصوصية هذه كيف يتعامل تطبيق **«موجة» (`Mawja - Arabic Radio & Podcast`)**، الذي تطوّره وتديره **Novyra**، مع البيانات والمعلومات عند استخدامك للتطبيق على أجهزة Android. صُمّم التطبيق ليوفّر تجربة استماع للإذاعات المباشرة والبودكاست دون الحاجة إلى إنشاء حساب مستخدم أو تسجيل دخول.

---

### 2. البيانات التي يجمعها التطبيق أو يعالجها فعلياً

#### أ. البيانات التي يقدّمها المستخدم طوعاً (تُخزَّن محلياً على جهازك فقط)
لا يطلب التطبيق اسمك أو بريدك الإلكتروني أو رقم هاتفك أو إنشاء حساب. جميع التفضيلات التي تنشئها داخل التطبيق تُحفظ **محلياً داخل ذاكرة جهازك فقط** (`SharedPreferences` والتخزين الداخلي الخاص بالتطبيق)، وتشمل:
- المحطات المفضلة ومجموعات/مجلدات المفضلة المخصصة التي تنشئها.
- سجل الاستماع الأخير (آخر 12 محطة أو حلقة استمعت إليها).
- حلقات البودكاست التي تختار تنزيلها للاستماع بدون إنترنت وموضع التوقف في كل حلقة.
- إعدادات المظهر والصوت والشبكة (الوضع الداكن، لون الهوية، المعادل الصوتي، مؤقت النوم، وضع توفير البيانات).

> **ملاحظة تقنية:** تم ضبط التطبيق برمجياً على تعطيل النسخ الاحتياطي السحابي التلقائي لبيانات التطبيق (`android:allowBackup="false"`).

#### ب. بيانات الموقع الجغرافي التقريبي (اختيارية وعند الطلب فقط)
- يطلب التطبيق إذن الموقع التقريبي (`android.permission.ACCESS_COARSE_LOCATION`) **فقط إذا ضغطت بنفسك على زر «تحديد الموقع»** داخل قسم «محطاتك المحلية».
- يُستخدم هذا الإذن حصرياً لتحديد رمز الدولة واسم المدينة محلياً بهدف عرض الإذاعات المحلية الخاصة ببلدك في واجهة التطبيق.
- لا يقوم التطبيق بتتبع موقعك في الخلفية ولا يرفع إحداثيات موقعك الجغرافي إلى أي خادم تابع للمطور.
- في حال عدم منح إذن الموقع، يعتمد التطبيق على رمز دولة شريحة الاتصال (`SIM/Network ISO`) أو المنطقة الزمنية للجهاز، أو استعلام شبكة خفيف عبر بروتوكول HTTPS (`api.country.is` أو `get.geojs.io`) لمعرفة رمز الدولة فقط (`Country Code`).

#### ج. البيانات التي تجمعها حزم الطرف الثالث الإعلانية (Google AdMob & Google UMP)
يستخدم التطبيق حزمة **Google Mobile Ads SDK (`com.google.android.gms:play-services-ads`)** لعرض إعلانات البانر، وحزمة **Google User Messaging Platform (`com.google.android.ump:user-messaging-platform`)** لإدارة موافقة المستخدم وخيارات الخصوصية.
قد تقوم شركة Google تلقائياً بجمع ومعالجة البيانات التالية لأغراض عرض الإعلانات (المخصصة أو غير المخصصة حسب موافقتك)، وقياس أداء الإعلانات، ومنع الاحتيال:
- معرّف الإعلانات الخاص بنظام أندرويد (`Google Advertising ID`).
- عنوان بروتوكول الإنترنت (`IP Address`) الذي قد يُستخدم لتقدير الموقع الجغرافي العام (الدولة/المدينة).
- معلومات الجهاز الأساسية (طراز الجهاز، إصدار نظام التشغيل، لغة النظام، أبعاد الشاشة).
- بيانات التفاعل مع الإعلانات المعروضة وبيانات تشخيص الأعطال المرتبطة بحزمة الإعلانات.

---

### 3. الاتصالات الشبكية ومصادر المحتوى الخارجية
لتشغيل البث الإذاعي والبودكاست، يتصل جهازك مباشرةً عبر بروتوكول `HTTPS` بالمصادر الصوتية والدلائل العامة التالية:
1. **خوادم البث الإذاعي المباشر وخوادم ملفات البودكاست (RSS & Audio Streams):** عند تشغيل أي محطة أو حلقة بودكاست، يتصل جهازك مباشرةً بخادم البث الخاص بتلك المحطة أو الناشر، ما يعني أن خادم المحطة يستقبل عنوان `IP` ونوع المشغّل كبروتوكول إنترنت قياسي لتوصيل الصوت.
2. **دليل الإذاعات العالمي (`Radio-Browser API`) ودليل إذاعات القرآن الكريم (`MP3Quran API`):** لجلب قوائم المحطات الإذاعية المحدثة.
3. **دليل بودكاست آبل (`Apple iTunes Search API`):** للبحث عن برامج البودكاست العربية وجلب روابط خلاصاتها (`RSS Feeds`).
4. **واجهة يوتيوب (`YouTube / InnerTube`):** لاستخراج البث الصوتي والصور المصغرة لقوائم التشغيل التي تعمل كإذاعات مستمرة 24/7.

---

### 4. الأذونات المطلوبة في التطبيق والغرض منها
- **`INTERNET` و `ACCESS_NETWORK_STATE`:** للاتصال بخوادم البث الإذاعي والبودكاست، ومراقبة حالة الشبكة لإعادة الاتصال التلقائي عند انقطاع الإنترنت، وتحميل الإعلانات.
- **`ACCESS_COARSE_LOCATION` (اختياري):** لتحديد الدولة والمدينة عند طلب المستخدم عرض المحطات المحلية.
- **`FOREGROUND_SERVICE` و `FOREGROUND_SERVICE_MEDIA_PLAYBACK` و `WAKE_LOCK`:** للسماح باستمرار تشغيل الصوت في الخلفية وعند قفل الشاشة مع إظهار إشعار التحكم بالمشغّل.

---

### 5. أغراض استخدام البيانات والأساس القانوني
تُعالج البيانات للأغراض المحددة التالية:
- **تشغيل الخدمة الأساسية:** بث الإذاعات وحلقات البودكاست وحفظ مفضلاتك محلياً على جهازك.
- **تخصيص التجربة المحلية:** عرض محطات بلدك تلقائياً دون الحاجة للبحث اليدوي.
- **تمويل التطبيق واستمراريته مجاناً:** عرض إعلانات البانر عبر Google AdMob مع احترام خيارات الموافقة الخاصة بك (وفق متطلبات GDPR و UK GDPR و KVKK وغيرها من القوانين المعمول بها).

---

### 6. تخزين البيانات، مشاركتها، ونقلها عبر الحدود
- **التخزين المحلي:** تبقى بيانات المفضلة وسجل الاستماع والحلقات المنزلة محفوظة على جهازك طوال فترة تثبيت التطبيق، أو حتى تقوم بمسحها بنفسك من داخل التطبيق أو بحذف التطبيق.
- **عدم بيع البيانات:** لا تبيع **Novyra** أي بيانات شخصية لأي طرف ثالث، ولا تمتلك قاعدة بيانات سحابية لجمع بيانات المستخدمين الشخصية.
- **مقدمو الخدمات الخارجيون والنقل الدولي:** قد تتم معالجة البيانات التي تجمعها خدمة Google AdMob أو خوادم البث الإذاعي العالمية على خوادم تقع خارج بلد إقامتك وفقاً لسياسات الخصوصية المعتمدة لدى تلك الجهات:
  - سياسة خصوصية Google: [https://policies.google.com/privacy](https://policies.google.com/privacy)

---

### 7. حقوقك والتحكم في بياناتك وحذفها
يمكّنك التطبيق ونظام Android من التحكم الكامل في بياناتك في أي وقت:
1. **مسح سجل الاستماع:** من داخل التطبيق عبر تبويب **«الإعدادات» ← «الخصوصية» ← «سجل الاستماع» ← «مسح السجل»**.
2. **حذف حلقات البودكاست المنزّلة:** من تبويب **«بودكاست»** بالضغط على أيقونة الحذف بجانب أي حلقة منزّلة.
3. **إدارة موافقة الإعلانات (Privacy Options):** عند انطباق لوائح حماية البيانات (مثل المنطقة الاقتصادية الأوروبية والمملكة المتحدة)، يظهر خيار **«خيارات خصوصية الإعلانات»** داخل تبويب **«الإعدادات»** لمراجعة أو سحب الموافقة على الإعلانات المخصصة في أي وقت.
4. **إعادة تعيين أو حذف معرّف الإعلانات:** من إعدادات جهاز Android (**الإعدادات ← الخصوصية ← الإعلانات ← إعادة تعيين معرّف الإعلانات / حذف معرّف الإعلانات**).
5. **إلغاء إذن الموقع:** من إعدادات تطبيقات نظام Android في أي وقت دون أن يتأثر تشغيل المحطات.
6. **الحذف الكامل:** يؤدي إلغاء تثبيت التطبيق من جهازك إلى حذف جميع البيانات والتفضيلات والملفات المخزنة محلياً بشكل فوري ونهائي.

---

### 8. خصوصية الأطفال
تطبيق «موجة» موجّه للجمهور العام من جميع الأعمار للاستماع إلى الإذاعات العامة والقرآن الكريم والبودكاست، ولكنه غير موجّه خصيصاً للأطفال دون سن 13 عاماً، ولا يجمع المطور عمداً أي بيانات شخصية من الأطفال.

---

### 9. حماية البيانات
يلتزم التطبيق باستخدام اتصالات مشفّرة حصرياً (`HTTPS` مع تفعيل `usesCleartextTraffic="false"`) والتحقق من سلامة الروابط الخارجية لمنع الاتصال بالشبكات المحلية أو غير الآمنة.

---

### 10. التغييرات على سياسة الخصوصية
قد نقوم بتحديث سياسة الخصوصية هذه عند إضافة ميزات جديدة أو لتلبية متطلبات قانونية أو تقنية. سيتم نشر أي تحديث على هذه الصفحة مع تحديث «تاريخ آخر تحديث» في أعلى الوثيقة.

---

### 11. التواصل معنا
إذا كان لديك أي استفسار أو طلب يتعلق بهذه السياسة أو بخصوصيتك، يمكنك التواصل مع المطور (**Novyra**) مباشرةً عبر البريد الإلكتروني:
- **البريد الإلكتروني:** [apps.novyra@gmail.com](mailto:apps.novyra@gmail.com)

---
---

## Part II: Privacy Policy (English Version)

### 1. Introduction
This Privacy Policy explains how **Mawja - Arabic Radio & Podcast** ("**Mawja**", package name: `com.volume.radio`), developed and published by **Novyra**, handles information when you use our Android application. Mawja is designed to provide live radio and podcast streaming without requiring user registration or login accounts.

### 2. Information Processed by the Application

#### A. User Preferences & Local Data (Stored Only on Your Device)
We do not ask for your name, email address, phone number, or account registration. Data created while using the app is stored **exclusively on your device** (`SharedPreferences` and internal app storage) with cloud auto-backup disabled (`android:allowBackup="false"`):
- Favorite stations and custom favorite folders/playlists.
- Recent listening history (up to the last 12 stations or episodes).
- Podcast episodes downloaded for offline listening and their playback resume positions.
- Theme, audio equalizer, buffer profile, sleep timer, and data-saver preferences.

#### B. Approximate Location Data (Optional & User-Initiated)
- The app declares `android.permission.ACCESS_COARSE_LOCATION` and requests it **only when you explicitly tap the "Detect Location" button** in the Local Stations section.
- Location data is used solely on your device to identify your country code and city name so the app can display local radio stations from your country.
- Novyra does not track your location in the background and does not transmit your GPS/network coordinates to any developer server.
- When location permission is not granted, the app determines your country code using SIM/network country ISO, device timezone/locale, or an HTTPS country-code lookup (`api.country.is` / `get.geojs.io`).

#### C. Third-Party Advertising & Consent SDKs (Google AdMob & Google UMP)
The app integrates **Google Mobile Ads SDK (`com.google.android.gms:play-services-ads`)** to display banner advertisements and **Google User Messaging Platform (`com.google.android.ump:user-messaging-platform`)** to manage user consent where required by law (such as GDPR / UK GDPR).
Google may automatically collect and process:
- Android Advertising ID (`AdID`).
- IP address (which may be used to estimate general country/city location).
- Device information (device model, OS version, language, screen dimensions).
- Ad interaction events and SDK diagnostic/performance data for ad delivery, measurement, and fraud prevention.
- Learn more at Google's Privacy Policy: [https://policies.google.com/privacy](https://policies.google.com/privacy)

### 3. Direct Network Connections to Content Sources
To stream audio and load directories, the app connects directly over `HTTPS` to:
1. **Third-Party Radio Stream Servers & Podcast Publishers:** Streaming a station or podcast connects your device directly to that broadcaster's server, which receives your IP address and standard HTTP player headers to deliver the audio stream.
2. **Public Directories:** `Radio-Browser API`, `MP3Quran API`, `Apple iTunes Search API` (for podcast discovery), and `YouTube InnerTube` (for 24/7 playlist stations).

### 4. Your Controls & Data Deletion
- **Clear Listening History:** Go to **Settings → Privacy → Listening History → Clear History** inside the app.
- **Delete Downloaded Podcasts:** Tap the delete icon next to any downloaded episode in the **Podcasts** tab.
- **Manage Ad Privacy / Consent Options:** Where applicable, open **Settings → Privacy → Ad Privacy Options** in the app, or reset/delete your Advertising ID in your Android system settings.
- **Complete Deletion:** Uninstalling the application permanently deletes all locally stored preferences, history, and downloaded files from your device.

### 5. Children's Privacy
Mawja is intended for a general audience across all ages and is not specifically directed at children under the age of 13. We do not knowingly collect personal information from children.

### 6. Contact Us
For any privacy questions or requests, please contact **Novyra** at:
- **Email:** [apps.novyra@gmail.com](mailto:apps.novyra@gmail.com)
