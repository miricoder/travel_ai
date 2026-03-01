# Itinerary Dashboard (GitHub Pages)

This folder contains a single-page itinerary dashboard (HTML) with:
- Dotted travel timeline
- Editable items (flights / lodging / events / to-dos)
- Cost summary chart (based on **Expense** items)
- LocalStorage persistence (your edits stay in your browser)

## Publish on GitHub Pages (recommended)

1. Create a GitHub repository (public is simplest), for example: `trip-itinerary`
2. Upload `index.html` (from this download) to the repository root
3. In GitHub: **Settings → Pages**
4. **Source:** Deploy from branch → `main` → `/(root)`
5. Visit the URL GitHub provides (usually `https://<username>.github.io/<repo>/`)

### Want a root URL like `https://<username>.github.io/`?
Create a repo named exactly: `<username>.github.io` and place `index.html` in the root.

## Offline use
You can open `index.html` directly on your laptop/phone (no internet needed). Your edits save locally in the browser.

## Data backup
Use **Export JSON** in the page to save your itinerary data, and **Import JSON** to restore it later.
