# Snap2HTML Tools — Filter & Extractor

A single-file, offline browser tool for working with [Snap2HTML](https://www.rlvision.com/snap2html/) folder snapshots. Load one or many snapshots, filter and extract file lists, group episodes into series, classify everything (movie, series, game…), and build a searchable HTML library of your collection.

No installation, no server, no upload: open `Snap2HTML_Filter.html` in a desktop or mobile browser. Everything runs locally.

**Version:** 15 · **UI languages:** 12 (English, العربية, Français, Deutsch, Español, Türkçe, Português, Русский, 中文, 日本語, 한국어, हिन्दी) · **Themes:** 9 decade-based themes (1970s → 2050s)

## 🌐 Open Source

This project is **open source** and available for everyone to use, modify, and improve.

⭐ **If you find it useful, please give the repository a Star.**  
🍴 **Fork it** if you want to add features, customize it, or build your own version.  
💡 Have a suggestion, found a bug, or have an idea for improvement? Open an **Issue**, submit a **Pull Request**, or contact me.

Every contribution and piece of feedback is welcome and appreciated.

## Tools (tabs)

| # | Tab | What it does |
|---|-----|--------------|
| 1 | **Filter & Extractor** | Load several Snap2HTML files (all Snap2HTML data versions), filter by extension, minimum size, name and folder, then export TXT / Excel-CSV or copy. Choose columns, path style, and add custom columns. |
| 2 | **Snap2HTML Clone** | Scan a folder from your computer (desktop only) and generate a Snap2HTML-compatible snapshot. |
| 3 | **Enhance Data** | Open an exported TXT/CSV, edit any cell, and re-export. |
| 4 | **Merge & Compare** | Load two exported lists, sort by a column (e.g. year), see rows missing that value, pick rows from either side, and export the merge. |
| 5 | **Finalizer** | Classify every item and build a standalone library page (details below). |
| 6 | **Grouper** | Select multiple items (e.g. episodes) and group them into one item. |

## Grouper

1. Load Snap2HTML `.html`, exported `.txt` / `.csv`, or a saved session `.json`.
2. Tick several items (click, or Shift+click for a range; use search to narrow the list) and press **Group selected**.
3. The grouped items disappear from the left list and appear as one entry (name, file count, total size) on the right. Repeat as often as needed; **Ungroup** reverses it.
4. Export TXT/CSV: only groups + still-ungrouped items are exported. **Save session** lets you continue later. **Send to Finalizer** passes the result on.

## Finalizer

Load snapshots, exported lists, Grouper output, or a saved project. Every item starts checked. Click an item to edit it:

- **Type:** Movie, Series, Game, Movie/Series in a Universe, Game in a Series, Music, Software, Book, Other. The type, name and year are guessed from the filename and can be corrected.
- **Fields:** name, year, platform (games), universe/series and part number, IMDb link, poster (resized and embedded), size (kept from the source).
- **Advanced (optional):** wallpaper path, subtitle path, genre, quality, language, rating, tags, notes.
- **Finalize & Build Library** creates `library.html`: an offline page with search, type/year filters, sorting (name, year, size, universe), a poster grid and expandable details. Unchecked items are left out.
- **Save project** stores your work as JSON so you can resume.

## Supported inputs

- Snap2HTML `.html` snapshots (legacy and modern data formats)
- TXT (tab-separated) or CSV exported by this tool (must contain a `Name` column)
- Saved Grouper sessions / Finalizer projects (`.json`)

## Notes

- Works in current Chrome, Edge, Firefox and Safari. Folder scanning (Clone tab) needs a desktop browser.
- Embedded posters increase the size of `library.html`; wallpaper and subtitle are stored as paths.
- The Grouper/Finalizer interface is currently English-only.

---

# العربية 🇸🇾

## Snap2HTML Tools — أدوات الفلترة والاستخراج

أداة تعمل من خلال **ملف HTML واحد وبدون إنترنت** للتعامل مع لقطات مجلدات **Snap2HTML**.

تتيح لك الأداة تحميل لقطة واحدة أو عدة لقطات، فلترة واستخراج قوائم الملفات، تجميع الحلقات ضمن مسلسل واحد، تصنيف العناصر (فيلم، مسلسل، لعبة...) وإنشاء مكتبة HTML قابلة للبحث والفلترة.

**لا تحتاج إلى تثبيت أو سيرفر أو رفع ملفات:** افتح `Snap2HTML_Filter.html` من متصفح الكمبيوتر أو الهاتف، وجميع البيانات تتم معالجتها محليًا على جهازك.

### 🌐 المشروع مفتوح المصدر

هذا المشروع **مفتوح المصدر (Open Source)** ومتاح للجميع للاستخدام والتعديل والتطوير.

⭐ إذا وجدت الأداة مفيدة، **لا تنسَ إعطاء المشروع Star على GitHub** لدعم المشروع.  
🍴 يمكنك **عمل Fork** إذا أردت إضافة ميزات جديدة أو تعديل الأداة أو إنشاء نسخة خاصة بك.  
💡 لديك اقتراح، فكرة لتطوير الأداة، أو وجدت مشكلة؟ يمكنك فتح **Issue** أو إرسال **Pull Request** أو التواصل معي مباشرة.

أي مساهمة أو ملاحظة منكم مرحب بها ومقدّرة ❤️

### 🛠️ الأدوات

| # | الأداة | ماذا تفعل؟ |
|---|---|---|
| 1 | **Filter & Extractor** | تحميل عدة ملفات Snap2HTML، الفلترة حسب الامتداد والحجم والاسم والمجلد، ثم تصدير النتائج إلى TXT / Excel-CSV أو نسخها. |
| 2 | **Snap2HTML Clone** | فحص مجلد من الكمبيوتر وإنشاء Snapshot متوافق مع Snap2HTML. تعمل هذه الميزة على الكمبيوتر فقط. |
| 3 | **Enhance Data** | فتح ملفات TXT/CSV المصدرة وتعديل الخلايا ثم إعادة تصديرها. |
| 4 | **Merge & Compare** | مقارنة قائمتين مصدرتين، ترتيبهما حسب أحد الأعمدة، معرفة العناصر الناقصة واختيار العناصر من أي قائمة ثم دمجها وتصديرها. |
| 5 | **Finalizer** | تصنيف العناصر وإنشاء صفحة مكتبة مستقلة قابلة للبحث والفلترة. |
| 6 | **Grouper** | اختيار عدة عناصر، مثل حلقات مسلسل، وتجميعها ضمن عنصر واحد. |

### 📦 أداة Grouper

1. حمّل ملف Snap2HTML بصيغة `.html` أو ملف `.txt` / `.csv` أو جلسة محفوظة بصيغة `.json`.
2. اختر عدة عناصر واضغط **Group selected**.
3. تختفي العناصر المجمعة من القائمة اليسرى وتظهر كعنصر واحد في الجهة اليمنى، مع الاسم وعدد الملفات والحجم الإجمالي.
4. يمكنك استخدام **Ungroup** لإلغاء التجميع، وحفظ الجلسة للمتابعة لاحقًا، أو إرسال النتيجة إلى **Finalizer**.

### 🏗️ أداة Finalizer

يمكنك تحميل Snapshots أو القوائم المصدرة أو نتائج Grouper أو مشروع محفوظ، ثم تعديل نوع ومعلومات كل عنصر.

- **Finalize & Build Library:** إنشاء ملف `library.html` مستقل يعمل بدون إنترنت، ويحتوي على البحث والفلاتر والترتيب وشبكة البوسترات والتفاصيل القابلة للتوسيع.
- **Save project:** حفظ العمل بصيغة JSON للعودة إليه لاحقًا.

### 📥 الملفات المدعومة

- Snap2HTML `.html` بجميع صيغ البيانات القديمة والحديثة.
- TXT أو CSV صادر من الأداة، ويجب أن يحتوي على عمود `Name`.
- جلسات Grouper ومشاريع Finalizer بصيغة `.json`.

### 📝 ملاحظات

- تعمل الأداة على الإصدارات الحالية من Chrome وEdge وFirefox وSafari.
- ميزة فحص المجلدات في **Clone** تحتاج إلى متصفح على الكمبيوتر.
- تضمين البوسترات داخل `library.html` قد يزيد حجم الملف.
- مسارات الخلفيات والترجمات يتم الاحتفاظ بها كمسارات.
- واجهة Grouper وFinalizer حاليًا باللغة الإنجليزية فقط.

---

## ❤️ Support & Contribute

If this tool saves you time or helps you organize your collection:

⭐ **Star the repository** · 🍴 **Fork it** · 🐛 **Report bugs** · 💡 **Share suggestions** · 🔧 **Submit a Pull Request**

إذا ساعدتك الأداة أو وفرت عليك الوقت: **اعمل Star للمشروع، اعمل Fork، شارك اقتراحاتك، وأرسل Pull Request للمساهمة في تطويرها.**

**Design & Development by Eng. Hussein Al-Haj Ali.**
