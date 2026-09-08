Moneywise CFL Dashboard - GitHub Pages / PWA Setup

Repository:
https://github.com/regionalcflmis/cfldashboard

UPLOAD THESE FILES/FOLDERS TO THE ROOT OF THE REPOSITORY:
1. index.html
2. manifest.json
3. service-worker.js
4. icons/icon-192.png
5. icons/icon-512.png

GITHUB STEPS
1. Open: https://github.com/regionalcflmis/cfldashboard
2. Click Add file > Upload files.
3. Upload index.html, manifest.json, service-worker.js and the icons folder contents.
   If GitHub web upload does not preserve the icons folder easily, create a folder named icons first, then upload both PNG files into it.
4. Commit changes to main.
5. Open Settings > Pages.
6. Under Build and deployment, select: Deploy from a branch.
7. Branch: main. Folder: /(root). Click Save.
8. Wait 1-3 minutes.
9. Open: https://regionalcflmis.github.io/cfldashboard/

INSTALL AS MOBILE APP
Android/Chrome or Edge:
- Open the GitHub Pages URL.
- Menu > Install app / Add to Home screen.

iPhone/iPad Safari:
- Open the GitHub Pages URL.
- Share > Add to Home Screen.

IMPORTANT
- PWA/service worker works on HTTPS (GitHub Pages provides HTTPS), not from file:/// local paths.
- When dashboard content is updated later, replace index.html and bump CACHE_NAME in service-worker.js (for example v2) so phones receive the new cached version.
