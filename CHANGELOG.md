# Changelog

All notable changes to ImgToPDF are documented here.

---

## v1.1 — May 2026

### Fixed
- Phone images no longer render rotated in the PDF. Root cause: jsPDF reads raw pixel data and ignores the EXIF orientation tag that phone cameras embed in images. Fix: images now pass through an HTML canvas before being handed to jsPDF — browsers apply EXIF orientation automatically when drawing to canvas, so the output always matches what you see on screen.

---

## v1.0 — 2025

### Released
- Browser-based image to PDF converter — no installs, no login, no data uploaded
- Two layout modes: A4 Centered and Plain
- Drag-and-drop support with auto A→Z sorting and manual reorder
- Light/Dark theme toggle
- Custom filename before download

