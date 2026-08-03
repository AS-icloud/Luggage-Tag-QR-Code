LUGGAGE TAG QR DESIGNER PWA

UPLOAD ALL FILES IN THIS FOLDER TO THE SAME GITHUB PAGES OR NETLIFY DIRECTORY.

Files:
- index.html            Shape, polygon, hole, mirrored-back and virtual-paper designer
- qr-generator.html     QR contact-data generator
- viewer.html           Page opened after a generated QR is scanned
- manifest.json         PWA installation information
- sw.js                 Offline cache
- icon-192.png          Application icon
- icon-512.png          Application icon
- icon.svg              Editable source icon

PWA installation and offline caching require HTTPS. GitHub Pages and Netlify
both provide HTTPS. Opening index.html directly with a file:// address is useful
for testing, but the browser cannot install its service worker in file mode.

After uploading an update:
1. Open the hosted index.html once while online.
2. Refresh the page.
3. On iPhone/iPad use Share > Add to Home Screen.
4. On supported desktop browsers use Install App.

Printing:
- Use Scale 100% / Actual Size.
- Disable Fit to Page.
- Confirm A4 or A5 matches the virtual-paper choice.
