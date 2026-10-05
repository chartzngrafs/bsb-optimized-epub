# E-Ink Optimized Bible Editions: Quick Reference & Guide

Welcome! This folder contains complete, high-contrast, distraction-free EPUB editions of the **Berean Standard Bible (BSB)** and **Majority Standard Bible (MSB)**, engineered specifically for dedicated E-Ink hardware.

---

## 1. Available Editions

| File | Translation | Profile | Size | Best Suited For |
|---|---|---|---|---|
| [`bsb_pocket_button.epub`](bsb_pocket_button.epub) | Berean Standard Bible | Pocket-Button | 2.96 MB | XTEINK X4, pocket e-readers, button-operated devices |
| [`bsb_larger_touch.epub`](bsb_larger_touch.epub) | Berean Standard Bible | Larger-Touch | 3.25 MB | Kobo, Kindle, Boox, PocketBook, KOReader |
| [`msb_pocket_button.epub`](msb_pocket_button.epub) | Majority Standard Bible | Pocket-Button | 3.11 MB | XTEINK X4, pocket e-readers, button-operated devices |
| [`msb_larger_touch.epub`](msb_larger_touch.epub) | Majority Standard Bible | Larger-Touch | 3.41 MB | Kobo, Kindle, Boox, PocketBook, KOReader |

---

## 2. Choosing Your Translation

Both translations are faithful, transparent modern English translations dedicated to the **Public Domain** (CC0 1.0 Universal):

* **Berean Standard Bible (BSB)**:
  * Complete 66-book text pairing the Hebrew Masoretic Text with the Greek Critical Text (NA, SBL, ECM, TR).
  * Current 3rd Printing text snapshot (October 2, 2026 update).
  * Includes 4,854 translational and manuscript footnotes.
* **Majority Standard Bible (MSB)**:
  * Complete 66-book text pairing the BSB Hebrew Old Testament with the Greek Byzantine Majority Text (Robinson-Pierpont 2018 New Testament).
  * Includes 6,646 footnotes featuring a rich textual apparatus documenting variations between the Byzantine Majority text, modern Critical Texts (CT), and the Textus Receptus (TR).
  * Words added by translators for English grammatical completeness are rendered in standard classical italics (`<i class="add">`), matching traditional formal-equivalence Bible printing.

---

## 3. Choosing Your Hardware Profile

### Pocket-Button Edition
Designed for small screens (e.g. 4.3" E-Ink) and physical directional buttons:
* **2-Stage Fast Button Navigation**: Streamlines hardware chapter menus to only the 66 Books (~70 total items), enabling 3-second button scrolling from Genesis to Revelation.
* **Compact Chapter Hubs**: Interactive chapter grids fit comfortably on a single screen without vertical overflow.
* **Dedicated End-of-Book Notes**: Footnotes reside in separate notes pages at the end of each book, keeping scripture uninterrupted while providing instant bidirectional return links.
* **Distraction-Free**: No on-page touch banners, button bars, or extraneous chrome.

### Larger-Touch Edition
Designed for capacitive touchscreens (6.0"+ 300 PPI) and touch software like **KOReader**:
* **Dual-Mode EPUB3 Pop-up Footnotes**:
  * In KOReader, tapping a footnote marker (`[a]`) opens an instant pop-up dialog over the text without losing your place.
  * Optionally enable KOReader's *"In-page EPUB footnotes"* style tweak to display notes at the bottom of the page like a printed study Bible.
* **Capacitive Touch Hitboxes**: Footnote markers, scripture links, and chapter tiles feature expanded hitboxes (~48px) to prevent mis-taps.
* **3-Level Hierarchical TOC**: Expandable tree (`Testament → Book → Chapter`) in your device's native Table of Contents drawer.
* **1-Tap Navigation**: Tap any chapter header to return to that book's Chapter Matrix, or use the bottom navigation buttons (`← Prev`, `Overview`, `Next →`).

---

## 4. Reading Flow & Table of Contents

* **Seamless Reading Flow**: The book begins directly with `Cover → Title Page & Colophon → Genesis Hub → Genesis 1` with zero artificial blank screens or multi-page gaps.
* **Native Device Navigation**: Rather than cluttering the reading flow with a 1,200-page in-text Table of Contents, table of contents navigation is accessed through your e-reader's native TOC menu or drawer (supported via EPUB 3 `<nav>` and EPUB 2 NCX).

---

## 5. Attribution & Public Domain Dedication

The BSB and MSB texts are dedicated to the **Public Domain** under **CC0 1.0 Universal** / Open Translation License. We gratefully acknowledge:
* **[Bible Hub](https://biblehub.com)**, **[Berean Bible](https://bereanbible.com)** ([berean.bible](https://berean.bible)), and **[Majority Bible](https://majoritybible.com)** for providing open, unrestricted access to Scripture.
* The **Berean Bible Translation Committee** in cooperation with Bible Hub, Discovery Bible, unfoldingWord, OpenBible.com, and Bible Aquifer.
* The open-source **[bsb2usfm](https://github.com/BSB-publishing/bsb2usfm)** pipeline.
