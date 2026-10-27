# Changelog

All notable changes to the CBZ Converter, newest first. The version number is also shown in the app header.

## 1.0.0 - 2026-10-27
- First standalone release, moved out of a Claude artifact into its own app on Cloudflare, with its own web address.
- Installable as an app on phone and computer, and updates itself when a new version is published.
- Works offline once installed. The two libraries it needs (JSZip and pdf-lib) are now bundled instead of loaded from the internet. Only the page fonts still come from Google Fonts and fall back to system fonts when offline.
- Files are saved with the browser's normal download, since the app now runs on its own page.
- Same features as before: CBZ or ZIP to ZIP, one big PDF, one PDF per file, or one PDF per folder, in natural reading order. Nothing is uploaded.
