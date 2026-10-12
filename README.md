# Find My Table

Mobile web page to scan the barcode on a box label and see which table it belongs to (Saporiti code), with floor, destination, contract, model and the other boxes of the same table.

- `index.html` is self-contained: the Fantoni – Saporiti packing list and the barcode reader are inside the file, so it also works offline once loaded.
- The live camera viewfinder only works when the page is served over https (GitHub Pages, Vercel, Netlify). Opened as a local file, use "Take a photo" instead.
- To use a newer packing list, tap "Load another Excel list" on the page, or ask Claude to rebuild `index.html` with the new file.
