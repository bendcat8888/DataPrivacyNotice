# InnoGen Pharmaceuticals — Data Privacy Notice Page

A modern, responsive **Data Privacy Notice & Consent** HTML page for event registration, styled with a clean white outer background and a purple theme inspired by the InnoGen logo.

## Preview (Local)
You can open the page directly in a browser, but for best results (and to avoid any asset path issues), run a local server:

```powershell
cd "c:\Users\Benedic Cater\SynologyDrive\Software Development\Python Codes\_App HTML\DataPrivacyNotice"
python -m http.server 8000 --bind 127.0.0.1
```

Then open:
- http://127.0.0.1:8000/index.html

## Project Structure
- `index.html` — Main page (all HTML + CSS included)
- `favicon.png` — Browser tab icon
- `InnoGen.png` — Logo used in the header

## Customization
Open `index.html` and adjust:
- **Brand colors**: CSS variables under `:root` (e.g., `--brand`, `--brand-2`)
- **Logo**: update the `<img src="InnoGen.png" ...>` in the header
- **Content**: update the text inside the sections (What we collect, Retention, Rights, etc.)
- **Contact info**: update the DPO contact details under the “Contact” section

## Notes
- This is a static HTML page (no build step required).
- Print styling is included via `@media print`.

## Credits
Designed for InnoGen Pharmaceuticals Inc.
