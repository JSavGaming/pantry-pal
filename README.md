# Pantry Pal

A simple installable pantry inventory web app with barcode product lookup.

## Features
- Scan supported barcodes with your phone camera in supported browsers.
- Looks up barcode numbers in the free Open Food Facts database and fills in product names when available.
- Scanning a barcode already in your pantry increases its quantity by one.
- Add, edit, delete, and adjust quantities; assign categories and optional best-by dates.
- Search/filter, running-low count, and JSON backup/restore.
- Inventory is saved locally in the browser on that device.

## Enable GitHub Pages
1. Open the repository's **Settings** tab.
2. Select **Pages** in the left sidebar.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then click **Save**.
5. Wait a minute or two for the published site link to appear on the Pages screen.

## Install on your phone
1. Open the published HTTPS Pages link in your phone browser.
2. Android/Chrome: menu (⋮) → **Install app** or **Add to Home screen**.
3. iPhone/Safari: Share → **Add to Home Screen**.

## Important notes
- Product lookup uses Open Food Facts and needs internet access; some products won't be listed.
- Your pantry inventory stays in this browser/device. Export a backup before clearing browser data or switching phones.
- Automatic camera scanning depends on browser support for `BarcodeDetector`; if unavailable, use **Enter barcode**.
- Camera scanning and installable/offline behavior require HTTPS, which GitHub Pages provides.