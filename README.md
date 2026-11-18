# MarkRead

A lightweight, browser-based Markdown reader. Open the page, choose a folder or Markdown files, and read them with a clean preview.

## Features

- Open a folder (including subfolders) or individual `.md` files
- Clickable links between Markdown files, with anchor support
- Mermaid diagram rendering with zoom and drag-to-pan
- Light, dark, and paper reading themes
- Remembers your last selection (Chromium-based browsers)
- Auto-refreshes the open file when it changes on disk (Chromium-based browsers)
- Collapsible file list with search

## Usage

Open `index.html` in a browser, or visit the [hosted version](https://hmv-workspace.github.io/MarkRead/). Click **Open** in the left panel and choose **Folder** or **File(s)**.

Your files are read locally in the browser and are never uploaded.

## Browser support

- Chrome and Edge: full support, including remembering the last selection
- Firefox and Safari: folder and file selection works, but the selection is not remembered after a page refresh

## Dependencies

Loaded from CDNs at runtime:

- [marked](https://github.com/markedjs/marked) for Markdown rendering
- [DOMPurify](https://github.com/cure53/DOMPurify) for sanitizing rendered HTML
- [Mermaid](https://github.com/mermaid-js/mermaid) for diagrams

## License

MIT. See [LICENSE](LICENSE).
