# Seat Planner

A small, free web tool for teachers to plan the seating in a classroom.

Load a class list as PDF (with photos and names). The tool cuts it into
individual cards, which you drag onto the seats of a room layout. Then
export the seating plan as a PDF.

**Try it:** open the app and click **Load class list (PDF) → Try with example class**
(fictional names and cartoon pictures, from `example/example-class-list.pdf`).

## Features

- **PDF import**: detects photos and names automatically, including the header
  (class, subject, teacher). Scanned lists work with a grid mode.
- **Room layouts**: mini auditorium, classroom with desks for 2, single desks,
  U-shape, group tables, computer room – or design and save your own room.
- **Drag & drop** with swap, undo, and *Random*, *Random (front)* and
  *Alphabetical* placement.
- **Labels**: "First L.", "First Last" or first name only, plus an optional
  extra line per student (e.g. hobby, elective).
- **View** from the teacher's side (board at the bottom) or from the back.
- **Several classes**, each with its own seating plan, shown as tiles.
- **Export PDF** (A4), file name with today's date.
- Works on computer and iPad (touch).

## Privacy

No login, no ads, no tracking – completely free.
Everything runs in the browser. Class lists, photos and plans are stored only
in the browser's own local database (IndexedDB) on that device – not in the cache.
The PDF itself is not saved. Nothing is uploaded.

The PDF reader [pdf.js](https://github.com/mozilla/pdf.js) (Mozilla, Apache License 2.0)
is included in the folder `pdfjs`, so the app needs no external server.

## Hosting

Upload `index.html` **together with the folder `pdfjs`** to any web server, or
enable **GitHub Pages** for this repository (Settings → Pages → branch `main`, folder `/`).

---

© 2026 AxlKray · Switzerland
