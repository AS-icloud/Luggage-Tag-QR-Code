LUGGAGE TAG QR DESIGNER PWA

UPLOAD ALL FILES IN THIS FOLDER TO THE SAME GITHUB PAGES OR NETLIFY DIRECTORY.

Files:
- index.html            Shape, polygon, hole, mirrored-back and virtual-paper designer
- qr-generator.html     QR contact-data generator
- viewer.html           Page opened after a generated QR is scanned
- luggage.html          Short fixed contact page used by the ready-made luggage-tag QR
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
- The tag is printed without scaling; left defaults to 2 mm and top defaults to 7 mm, and both are editable.
- Print, PDF, SVG, PNG and JPG all use the selected virtual paper and the same placement values. PDF and SVG are preferred when exact physical sizing is most important; PNG and JPG use the selected DPI.
- The fold allowance remains visible in the working preview for measurement, but its coloured band, dashed lines and wording are omitted from every saved or printed output.
- Safari print-to-PDF uses an out-of-flow label image so A4, A5 and 4 × 6 exports remain one page without an extra blank sheet.
- Use the supplied sample polygon and Address Label contact data, or Clear All to start empty.
- Drag the QR and each text/image window directly on the preview.
- Overlap windows remain in Overlap mode while dragged, may sit partly or fully outside the QR, and no longer cause the QR preview to disappear or revert to Custom position.
- Additional windows can be rectangles, squares or circles with independent text and rotation.
- The main window and every additional window support font scaling, optional borders, multiline text and image import. With background mode off, an imported camera image sits above text such as “Scan the QR”.
- The QR sample restores the last working fold-over layout and the supplied two-address contact data.
- Front and back QR boxes are independently draggable; use Reset QR Positions to restore automatic safe placement.
- Decorative QR-style dots are off by default. Every QR window includes a wide 4 mm white perimeter, and Print/PDF/PNG/SVG are blocked when the functional modules inside it fall below the reliable 0.35 mm target.
- QR scan visibility is independently selectable for Address 1/2, Mobile 1/2, Telephone 1/2, WhatsApp 1/2 and Email 1/2, plus name, organisation and notes.
- The PWA shows the familiar Shape & Print Designer first and the QR Content, Preview & Print section directly underneath it.
- Use “Apply these shape settings” to carry dimensions, fold, hole and front-window placement into the QR section.
- Print-tested defaults: 92 × 51 mm front and back, 2 mm fold, 18 × 16 mm corner cut, no printed hole guides, and a 57 × 10 mm front window. Align and punch the physical holes manually while pasting.
- The ready-to-print front QR opens l.html (https://as-icloud.github.io/LT/l.html). That page displays English beside a selectable Spanish, French, German, Italian, Portuguese, Hindi, Punjabi, Arabic, Simplified Chinese or Japanese column and can copy either version. The QR itself stays the same: the finder chooses their language after scanning. The older luggage.html address redirects to the shorter address.
- In QR Content, choose “Multilingual luggage page (short QR)”, then tick at least five languages. The generated QR uses the compact `l.html?l=...` address and shows English plus exactly those chosen languages after scanning.
- QR size warnings are advisory. The warning panel includes “Print anyway — I accept the QR warning”, and the virtual-print/save confirmation also lets you continue when the back QR is sufficient for your use.
- The front QR now defaults to exactly `https://as-icloud.github.io/LT/` with Medium correction. It contains no contact details, language codes or query parameters, so it is intended to fit a 23 × 23 mm QR window.
- In fold-over mode, the front always encodes that short URL. The selected QR content is encoded separately on the back, where detailed personal data or the multilingual page can be used.
- The ready-to-print back QR is an offline vCard. Contact values are stored once, with English, Spanish, French and German recovery messages plus the online page URL. It can be read without a live translation service.
