# SCDPM 6 Dashboard — Regional Labour Institute, Kolkata

A modern, mobile-responsive dashboard for showcasing campaign performance under the **Special Campaign for Disposal of Pending Matters (SCDPM 6.0)** & **Swachhata Hi Seva 2026** at Regional Labour Institute, Kolkata (Directorate General of Occupational Safety and Health, Ministry of Labour and Employment, Government of India).

## Contents

- `index.html` — Main executive campaign dashboard featuring real-time stat ribbons, interactive photo slideshow with touch-swipe & lightbox zoom, performance indicator cards, record management metrics, and statutory references.
- `admin-entry.html` — Full-featured Data Entry & Synchronization console with instant cross-tab live update, auto-calculated progress percentages, and JSON export.
- `data/performance-update.json` — Published baseline performance, record management, and references data.
- `data/initiatives.json` — Campaign initiatives and impact metrics.
- `gallery/gallery.json` — List of exhibition posters, captions, and dates.
- `gallery/images/` — Campaign high-resolution poster files.
- `gallery/index.html` — Standalone responsive gallery viewer with fullscreen modal lightbox.

## Key Features

1. **Executive Aesthetics**: Indian National Tricolor accent ribbon, institutional badges, clean typography (*Plus Jakarta Sans*), and elevated card designs.
2. **Real-time Live Sync**:
   - Updates saved in `admin-entry.html` are broadcasted **instantly** to open `index.html` tabs via `BroadcastChannel` and `localStorage` without requiring a page refresh.
   - Built-in status badge in the dashboard header indicating live sync state (`🟢 Local Sync Active` or `🌐 Official Published JSON`) with a 1-click toggle.
3. **Mobile-First Experience**:
   - Touch-swipe support on smartphones and tablets for photo slideshow.
   - Tap-to-zoom modal lightbox for reading high-res campaign posters.
   - Sticky bottom navigation bar for quick one-tap jumping between sections.
   - Sticky save bar in the data entry console for effortless updates on mobile.
4. **Data Management**:
   - Export one-click `performance-update.json` directly from `admin-entry.html` to commit official updates to GitHub Pages.

## Publish with GitHub Pages

1. Push your changes to the repository's `main` branch.
2. In the GitHub repository, navigate to **Settings → Pages**.
3. Under **Branch**, select `main` and `/ (root)` folder, then click **Save**.
4. Your dashboard will be live at `https://<username>.github.io/SCDPM6/`.

## Updating Campaign Performance

1. Open `admin-entry.html` in your browser.
2. Update the reporting date, officer details, 5 core indicators, record management rows, and statutory reference statuses.
3. Click **Save & Sync Dashboard** — any open dashboard tab updates immediately!
4. Click **Download data/performance-update.json** to replace `data/performance-update.json` in this repository and commit to GitHub to make the update permanent for all external visitors.

## Official Campaign Portal

[Swachhata Hi Seva (Government of India)](https://swachhatahiseva.gov.in/)

## License

See [`LICENSE.md`](LICENSE.md).
