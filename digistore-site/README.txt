DIGISTORE - 3D book website
===========================

Files
-----
index.html   The whole website (HTML + CSS + JavaScript in one file).

Run locally (the 3D needs a local server, not a double-click)
--------------------------------------------------------------
1. Open a terminal in this folder.
2. Run:  npx serve
3. Open the address it prints (usually http://localhost:3000).

Publish on GitHub Pages
-----------------------
git add .
git commit -m "DIGISTORE site"
git push
Then GitHub > Settings > Pages > Deploy from a branch > main / (root).

Things to edit in index.html
----------------------------
- Prices: search for  class="price"  and replace "Price on storefront".
- Storefront links: search for  href="#"  in the Superprofile and Gumroad cards.
- Colours: the :root block at the top of the <style> section.
- Book pages: the PAGES block in the module script.
- Internet is needed for the 3D library (three.js) and Google Fonts, both loaded from CDNs.
