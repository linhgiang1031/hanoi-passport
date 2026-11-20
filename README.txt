HANOI TRAVEL PASSPORT — NFC/PWA PROTOTYPE

1. Upload ALL files in this folder to the ROOT of a NEW PUBLIC GitHub repository (e.g. hanoi-passport).
2. In GitHub: Settings > Pages > Build and deployment > Deploy from a branch > main > /(root) > Save.
3. Wait for GitHub Pages to show your URL, usually https://YOURUSERNAME.github.io/hanoi-passport/
4. Open URL on phone while online; wait for it to load fully. Test language switch, visited markers, and export/import.
5. Open same URL again without internet to test cached PWA. Optionally use browser 'Add to Home Screen' for more reliable offline access.
6. NFC Tools > Write > Add a record > URL > paste the LIVE GitHub Pages URL > Write tag. NFC usually needs connectivity to launch URL unless OS/browser has cached it; offline launch via home-screen shortcut is more reliable.

IMPORTANT LIMITATIONS:
- Illustrated roads/water shapes are SCHEMATIC; GPS PIN positions are calculated from lat/lng. This is not a street-navigation map. Google Maps button handles navigation.
- First online load required; offline cache is best-effort and may be cleared by the OS/browser.
- Visited status is stored in localStorage on the same browser/device; different browsers or phones do not share it. Export/import backup is included.
- Google Maps directions are NOT bundled offline.
- No account, database, or admin website required.
- No paid map APIs are used.
