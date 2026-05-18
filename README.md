# PDF Merge Tool

A lightweight, single-page PDF merge tool that runs entirely in your browser. No uploads, no server, no installs — just drag, drop, and merge.

> **Note:** This project was generated using GitHub Copilot.

**[Live Demo →](https://olesia-kochergina.github.io/pdf-merge-tool)**

---

## Features

- **Drag & drop** PDF files directly onto the page
- **Click to browse** and select files via the file picker
- **Reorder files** by dragging them in the list before merging
- **100% local** — all processing happens in your browser via [pdf-lib](https://pdf-lib.js.org/)
- No file size limits beyond what your browser can handle
- Auto-downloads the merged PDF when done

## Usage

1. Open `index.html` in any modern browser (or visit the GitHub Pages URL above)
2. Drag PDF files onto the drop zone, or click **Add Files** to browse
3. Reorder the files if needed by dragging them in the list
4. Click **Merge PDFs** — the merged file downloads automatically

## Deployment (GitHub Pages)

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Set the source to the `main` branch, root folder (`/`)
4. Save — your tool will be live at `https://<your-username>.github.io/<repo-name>`

## Tech Stack

|              |                                                    |
| ------------ | -------------------------------------------------- |
| Language     | Vanilla HTML / CSS / JavaScript                    |
| PDF engine   | [pdf-lib](https://pdf-lib.js.org/) via CDN (unpkg) |
| Dependencies | None (single `index.html` file)                    |
| Hosting      | GitHub Pages                                       |

## Limitations

- Encrypted / password-protected PDFs are not supported
- Requires an internet connection to load pdf-lib from the CDN on first visit

## License

[MIT](LICENSE)
