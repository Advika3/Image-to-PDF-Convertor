# ImgToPDF

A lightweight, browser-based tool to convert images into a single PDF — no login, no data stored, no server, and safe!

---

## Link

[imgToPDF →](https://advika3.github.io/Image-to-PDF-Convertor/)

## Features

- **Two layout modes**
  - **A4 Centered** — image scaled to fit and centered on a white A4 page (210×297mm). Ideal for printing and assignment submissions.
  - **Plain** — each page is sized exactly to the image's native dimensions. Image fills the page edge-to-edge with no background or margins.
- **Multi-image support** — add multiple JPG/JPEG/PNG files; they are auto-sorted A→Z and can be manually reordered by drag-and-drop (please note that the drag-and-drop works only on desktop)
- **Custom filename** — name your output PDF before downloading.
- **Light/Dark theme** — toggleable via the nav bar.
- **100% client-side** — no files are uploaded to any server. Everything runs in the browser using [jsPDF](https://github.com/parallax/jsPDF).

---

## Usage

1. Open `index.html` in any modern browser.
2. Drop or select your images (JPG, JPEG, PNG).
3. Choose a layout — **A4 Centered** or **Plain**.
4. Enter a filename.
5. Click **Convert & Download PDF**.

---

## Tech Stack

| Concern | Solution |
|---|---|
| PDF generation | [jsPDF 2.5.1](https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js) via CDN |
| Fonts | Cormorant Garamond + DM Sans via Google Fonts |
| Hosting | None required — single static HTML file |

---

## Supported Formats

- Input: `.jpg`, `.jpeg`, `.png`
- Output: `.pdf`

---

## A Note on Process

The idea, design, UX decisions, and debugging were entirely mine. 
The JavaScript implementation was built with AI assistance (Claude by Anthropic) as I have primarily worked with Python so far. 
I also reviewed, tested, and iterated on every output until it worked correctly. 
Using AI as an implementation tool while owning the product decisions is a legitimate way to build,
and I'd rather be upfront about it than not :) 
