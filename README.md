# Snap2HTML Tools — Filter & Extractor

A single-file, offline browser tool for working with [Snap2HTML](https://www.rlvision.com/snap2html/) folder snapshots. Load one or many snapshots, filter and extract file lists, group episodes into series, classify everything (movie, series, game…), and build a searchable HTML library of your collection.

No installation, no server, no upload: open `Snap2HTML_Filter.html` in a desktop or mobile browser. Everything runs locally.

**Version:** 15 · **UI languages:** 12 (English, العربية, Français, Deutsch, Español, Türkçe, Português, Русский, 中文, 日本語, 한국어, हिन्दी) · **Themes:** 9 decade-based themes (1970s → 2050s)

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

**العربية:** أداة HTML واحدة تعمل بدون إنترنت للتعامل مع لقطات Snap2HTML: فلترة الملفات وتصديرها، تجميع الحلقات في مسلسل واحد، تصنيف العناصر (فيلم، مسلسل، لعبة…) وإنشاء مكتبة HTML قابلة للبحث والفلترة. جميع البيانات تبقى على جهازك.

*Design by Eng. Hussein Al-Haj Ali.*
