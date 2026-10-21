# SCDPM 6 Dashboard — Regional Labour Institute, Kolkata

A static dashboard for showcasing campaign performance under the **Special Campaign for Disposal of Pending Matters (SCDPM), 6.0 edition** at Regional Labour Institute, Kolkata.

## Contents

- `index.html` — campaign dashboard, including the campaign photo slider, Campaign Performance cards, References/Assurances/Process Reforms card, and Record Management.
- `admin-entry.html` — simplified Campaign Performance update form.
- `data/initiatives.json` — campaign initiative data.
- `gallery/gallery.json` — list of gallery images and captions.
- `gallery/images/` — campaign poster/image files.
- `gallery/index.html` — standalone gallery page.

## Publish with GitHub Pages

1. Upload the contents of this project folder to the repository's `main` branch.
2. In the repository, open **Settings → Pages**.
3. Select the `main` branch and `/ (root)` as the publishing source, then save.
4. Keep the folder structure intact so the dashboard can find the images under `gallery/images/`.

## Update Campaign Performance

1. Open `admin-entry.html` from the same website as the dashboard.
2. Update the reporting date and each indicator's target, daily achievement, and cumulative value.
3. Click **Save & Sync Dashboard**.
4. Open or reload `index.html` in the same browser and website origin to view saved values.

The current form uses browser `localStorage`. Saved values are local to that browser and website origin; they are not shared with other visitors and do not update files in GitHub automatically. Use **Download update JSON** to export a copy of the figures.

## Photos

The slideshow and gallery refer to image files under `gallery/images/`. When adding or replacing images, update `gallery/gallery.json` and preserve exact filenames and case.

## Official campaign portal

[Swachhata Hi Seva](https://swachhatahiseva.gov.in/)

## License

See [`LICENSE.md`](LICENSE.md). Confirm the copyright holder and license terms before publishing the repository.
