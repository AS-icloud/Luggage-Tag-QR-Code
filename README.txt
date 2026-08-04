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
- Choose A4 Virtual, A5 Virtual or 4 × 6 inch Virtual in the QR designer.
- Confirm the same paper size in the system print window.
- The tag is printed without scaling; left and top both default to 2 mm and are editable.
- Print, PDF, SVG and PNG all use the selected virtual paper and the same placement values.
- The fold allowance remains visible in the working preview for measurement, but its coloured band, dashed lines and wording are omitted from every saved or printed output.
- Safari print-to-PDF uses an out-of-flow label image so A4, A5 and 4 × 6 exports remain one page without an extra blank sheet.
- Use the supplied sample polygon and Address Label contact data, or Clear All to start empty.
- Drag the QR and each text/image window directly on the preview.
- Additional windows can be rectangles, squares or circles with independent text and rotation.
- The QR sample restores the last working fold-over layout and the supplied two-address contact data.
- Front and back QR boxes are independently draggable; use Reset QR Positions to restore automatic safe placement.
- The PWA shows the familiar Shape & Print Designer first and the QR Content, Preview & Print section directly underneath it.
- Use “Apply these shape settings” to carry dimensions, fold, hole and front-window placement into the QR section.
- Photo-measured defaults: 86 × 46 mm front, 2 mm fold, 18 × 16 mm corner cut, 5 mm hole and 57 × 10 mm front window.
