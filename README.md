# Bottle Finder

Sample multi-store liquor inventory search. Five stores, about 120 SKUs of example data, one search box that forgives typos, shorthand ("jd", "titos handle", "crown apple") and barcode prefixes.

- Open `index.html` in a browser, or run `node server.js` and visit http://localhost:8080
- All stock, prices and barcodes are invented. Only the brands are real.
- In production the page would read each store's POS (Square Catalog + Inventory API per location) every few minutes and match products across stores by UPC.
