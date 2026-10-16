THE MEASURE OF BEING — 3D FLIPBOOK STARTER

This starter contains the custom index.html, not the third-party viewer assets.

1. Download the FREE 3D FlipBook jQuery package (version 1.9.9) from:
   https://www.npmjs.com/package/flip-book
   Direct archive: https://registry.npmjs.org/flip-book/-/flip-book-1.9.9.tgz
   Alternatively follow https://3dflipbook.net/getting-started

2. Extract the archive. From the extracted package, COPY THE CONTENTS of:
   package/js/       -> this starter's js/
   package/css/      -> this starter's css/
   package/images/   -> this starter's images/
   package/fonts/    -> this starter's fonts/
   package/templates/-> this starter's templates/
   package/sounds/   -> this starter's sounds/
   package/dist/3dflipbook.min.js -> this starter's js/3dflipbook.min.js

   NOTE: Check that js/default-book-view.js and js/pdf.worker.js exist.
   The 3D FlipBook free package is GPL-2.0. Retain the original LICENSE
   file and comply with applicable license obligations.

3. Put ONLY your public preview PDF here:
   src/book-preview.pdf
   Do not upload the complete paid book.

4. Upload all contents of this starter folder (not the parent folder) to
   a PUBLIC GitHub repository, e.g. the-measure-of-being-flipbook.
   Keep the included .nojekyll file.

5. GitHub: Settings > Pages > Deploy from a branch > main > /(root) > Save.
   The page will normally be at:
   https://YOUR-USERNAME.github.io/the-measure-of-being-flipbook/

6. In Payhip Store Builder, insert a Custom HTML / embed block IF your
   selected Payhip page supports iframe HTML, and paste:

   <iframe src="https://YOUR-USERNAME.github.io/the-measure-of-being-flipbook/" title="The Measure of Being — Flipbook Preview" style="width:100%;height:740px;border:0;" loading="lazy" allowfullscreen></iframe>

   Replace YOUR-USERNAME. If Payhip strips iframe HTML, link to the
   GitHub Pages viewer instead.

IMPORTANT:
- This is a starter package, not a fully working viewer until the original
  third-party assets and your preview PDF are added.
- Test on desktop and mobile after publishing. The old 1.9.9 package uses
  legacy dependencies and may have compatibility issues in modern browsers.
- The public PDF can be retrieved even if download controls are hidden.
- The full paid book should remain on Payhip only.

Official documentation: https://3dflipbook.net/documentation
