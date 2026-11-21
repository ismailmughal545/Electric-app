# Create Panel (Electric-app)

Offline-capable drawing & text editor PWA (shapes, English/Urdu text, PNG/JPG export, photos from your gallery, project save/load).

- Open `index.html` through any static HTTP server (service worker needs http/https).
- Projects are stored in the browser (`localStorage`); use File → Save project to download a `.json` copy.
- Google Fonts are fetched on first use and cached for offline use afterwards.
