WWISK2 - PUBLIC LANDING PAGE ONLY

SAFE CONTENTS
- index.html: redirects root site to /wwisk2/
- wwisk2/index.html: public landing page (original HTML/CSS; no game files)
- .nojekyll: disables Jekyll transformation

DO NOT UPLOAD the previous FULL-GAME GitHub Pages ZIP, site.zip, game cards, private PDF, secrets, or existing private repository contents.

HOW TO PUBLISH USING GITHUB WEB
1) Create a NEW PUBLIC GitHub repository named exactly: gritsoonjun.github.io
   (Keep your EXISTING GritSoonjun/wwisk2 repository PRIVATE.)
2) In the new PUBLIC repo, upload index.html and .nojekyll to its root.
3) Click Add file > Create new file. Type: wwisk2/index.html
   Paste the contents of the included wwisk2/index.html file and commit to main.
   Alternatively use Git on PC to add the full directory tree.
4) Repo > Settings > Pages > Build and deployment:
   Source: Deploy from a branch
   Branch: main
   Folder: /(root)
   Save.
5) Website: https://gritsoonjun.github.io/wwisk2/

NOTE: This public page intentionally does NOT link to the Cloudflare Worker.
Share the private game address only through approved Discord conversations.
This alone DOES NOT make the current Cloudflare Worker private: publicly served
static files can still be fetched by anyone who discovers their URLs.
Protect static assets and confirm your rights to any third-party card content.

This package makes NO changes to the private GitHub repository or Cloudflare Worker.
