<div align="center">
<h1>Quran Metadata &mdash; بيانات عن القرآن الكريم</h1>
</div>

[src]: http://tanzil.net/docs/quran_data

This folder contains data about:
- each surah (`surah.json`),
- each sajda (`sajda.json`).
- each page (in Mushaf al-Madina) (`page.json`),
- each juz (`juz.json`),
- each rub-el-hizb (`rub.json`),
- each manzil (`manzil.json`), and
- each ruku (`ruku.json`).

Surah data (`surah.json`) includes the following data about each surah:
1. its number (`index`),
2. its Arabic name (`titleAr`),
3. its translated English name (`titleEn`),
4. its transliterated name (`title`),
5. its ayat number (`count`),
6. its type (`type`: `Makkiyah` or `Madaniyah`),
7. its rukus number (`rukus`),
8. its revelation order (`revelationOrder`),
9. its starting page in Mushaf al-Madina (`page`),
10. its parts with respect to the juz-partitioning (`juz`).
11. number of ayat in the Quran before this surah (e.g., 0 before al-Fatiha, 7 before al-Baqara, 7+286=293 before Aal-Imran, etc) (`start`).

Sajda data (`sajda.json`) includes the following data about each sajda:
1. its number,
2. data about its ayah (its number and data about its surah), and
3. whether it's obligatory or recommended.

The files about divisions of the Quran
(`juz.json`, `manzil.json`, `page.json`, `rub.json`, `ruku.json`)
contain the following data about each division:
1. its number (page number for pages, juz number for juzus (ajzaa), etc),
2. data about its first ayah (its number and data about its surah), and
3. data about its last ayah.

All these files except `juz.json` and `surah.json`
are based on [Tanzil Metadata][src];
only four fields in `surah.json`
are from Tanzil Metadata
(namely, `revelationOrder`, `rukus`, `titleEn`, and `start`).

<div dir="rtl">

## بيانات عن القرآن الكريم

يحتوي هذا المجلد على بيانات:
- السور (`surah.json`),
- السجدات (`sajda.json`).
- الصفحات (بمصحف المدينة) (`page.json`)
- والأجزاء (`juz.json`)
- وأرباع الأحزاب (`rub.json`)
- والمنازل (تقسيم القرآن إلى سبعة أقسام، المنقول عن الصحابة، وهو شائع في شبه القارة الهندية) (`manzil.json`)
- والركوعات (تقسيم موضوعي لكل سورة من سور القرآن، وهو شائع في شبه القارة الهندية) (`ruku.json`).

يحتوي ملف السور (`surah.json`) على البيانات التالية عن كل سورة:
1. رقمها (`index`),
2. اسمها بالعربية (`titleAr`),
3. ترجمة اسمها إلى الإنجليزية (`titleEn`),
4. اسمها العربي منقول صوتيا بالحروف الإنجليزية (`title`),
5. عدد آياتها (`count`),
6. مكية أم مدنية (`type`),
7. عدد الركوعات فيها (`rukus`),
8. ترتيب نزولها (`revelationOrder`),
9. رقم صفحتها بمصحف المدينة(`page`),
10. أقسامها بالنسبة إلى الأجزاء (`juz`).
11. عدد الآيات السابقة للسورة من بداية المصحف (الفاتحة صفر، والبقرة سبعة، وآل عمران ٧+٢٨٦ = ٢٩٣، إلخ)  (`start`).

يحتوي ملف السجدات (`sajda.json`) على البيانات التالية عن كل سجدة:
1. رقمها (ترتيبها بين السجدات)،
2. بيانات آيتها (رقمها، وبيانات سورتها)،
3. هل هي واجبة أم مستحبة.

ملفات التقسيمات
(`juz.json` و`manzil.json` و`page.json` و`rub.json` و`ruku.json`)
تحتوي على البيانات التالية عن كل تقسيم:
1. رقمه (رقم الصفحة في ملف الصفحات، رقم الجزء في ملف الأجزاء، إلخ)،
2. وبيانات أول آية فيه (رقمها، وبيانات سورتها)،
3. وبيانات آخر آية فيه.

جميع هذه الملفات عدا ملفي الأجزاء (`juz.json`) والسور (`surah.json`)
مأخوذة عن [بيانات القرآن الكريم من موقع تنزيل][src]؛
وأربعة حقول فقط في ملف السور
مأخوذة من بيانات تنزيل
(تحديدا ترتيب النزول `revelationOrder`، وعدد الركوعات `rukus`، والاسم بالإنجليزية `titleEn`، وعدد الآيات قبلها `start`).

