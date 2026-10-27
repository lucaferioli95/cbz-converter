# CBZ Converter

Turns CBZ/ZIP comic archives into ZIP files or PDFs, in natural reading order. Runs entirely in the browser, nothing is uploaded.

- App: https://cbz-converter.luca-ferioli95.workers.dev/
- Hosting: Cloudflare Workers static assets (`wrangler.jsonc`), deployed automatically on every push to `main`.
- Libraries are bundled: `jszip.min.js` 3.10.1, `pdf-lib.min.js` 1.17.1.
- Each release is listed in [CHANGELOG.md](CHANGELOG.md). When shipping, bump `APP_VERSION` in `index.html` and the `CACHE` name in `sw.js`.
