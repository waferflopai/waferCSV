# waferCSV — CSV to JSON Converter

**waferCSV** is a free, client-side web tool that converts CSV data to JSON instantly in your browser. No uploads, no sign-ups, no server—your data stays private.

👉 **Live demo:** [wafercsv.vercel.app](https://wafercsv.vercel.app/)

---

## ✨ Features

- **100% client-side** — your data never leaves your device
- **No uploads** — paste, drag & drop, or upload a file locally
- **Auto-detects delimiters** — comma, tab, semicolon, pipe, space
- **Interactive column management**
  - Rename columns
  - Change data types (`string`, `integer`, `float`, `boolean`, `date`, `null`)
  - Reorder columns via drag & drop
  - Select/deselect columns for output
- **Flexible output**
  - JSON Array or Hash (keyed by a column)
  - Three formatting options: Clean (2 spaces), Compact, Mini (single line)
- **Tree view** — browse nested JSON structure interactively
- **Raw JSON** — copy or download with one click
- **Undo/Redo** — changes to column configuration
- **Export** — download as `.json` or copy to clipboard
- **MIT Licensed** — free to use, modify, and share

---

## 🚀 How to Use

1. **Import** — paste CSV data, drag & drop a file, or use the upload button
2. **Configure** — select columns, set types, rename fields, adjust row range
3. **Export** — view as Tree or Raw, then download or copy

It's that simple.

---

## 🛠️ Installation

Clone the repo and open `index.html` in your browser:

```bash
git clone https://github.com/waferflopai/wafercsv.git
cd wafercsv
open index.html
