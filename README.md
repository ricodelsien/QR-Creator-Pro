# QR Studio

Create QR codes and contact banners in the browser. For links, plain text, and vCards, with a live preview and export. German and English.

**Nico Siedler © 2026**

## Use

Open `QR Studio.html` in the `ready` folder.

- One file. No server, no install.
- Works offline. Web fonts are optional; without a network connection the app uses a system font.
- Saved projects, colors, and drafts stay in the browser on this computer. Nothing is uploaded.
- To share the app, send that single HTML file. Saved projects are not included. Use the JSON export in the menu, and import it on the other side.

## Features

- QR codes for a link, text, or vCard
- Appearance: colors, shape, margin, readability, center logo
- Banner as a contact card, portrait or landscape, including without a QR code
- QR export as SVG, PNG, and JPG
- Banner export as HTML, SVG, PNG, and JPG
- Save and load projects locally

## Develop

```bash
npm install
npm run dev
```

Build the standalone file:

```bash
npm run package
```

This rewrites `ready/QR Studio.html`. On Windows you can also run `Build-Standalone.bat`.
