# Manufacturing Flow Designer — PWA Stage 1

Stage 1 is a touch-friendly, offline-capable process builder matching the WPF application concept.

## Included
- Dark CAD-style responsive UI for desktop, iPad and iPhone
- Project, customer, component and shift details
- Manual, automatic, walking, inspection and buffer resources
- Drag-and-drop or tap-to-add resources
- Move, select, duplicate and delete tasks
- Link tasks to define process order
- Task editor for cycle time, cost and notes
- Custom reusable resources
- Pan, pinch/wheel zoom and fit-to-view
- Local autosave, JSON `.mflow` import/export, undo/redo
- Browser print / Save as PDF
- Installable PWA with offline service worker

## Run locally
A service worker requires HTTP/HTTPS rather than opening `index.html` directly.

### Simple local server
From this folder run:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080`.

## GitHub Pages
Upload all files and folders to a repository, enable GitHub Pages from the repository settings, and open the published HTTPS address in Safari. Use **Share → Add to Home Screen** to install it as an app.
