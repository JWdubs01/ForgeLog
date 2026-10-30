ForgeLog iPhone PWA

IMPORTANT: iPhone cannot install this directly from the ZIP or a local file. Upload the contents of this folder to an HTTPS static host.

Install on iPhone:
1. Publish all files while preserving the folder structure.
2. Open the HTTPS address in Safari.
3. Tap Share.
4. Tap Add to Home Screen.
5. Ensure Open as Web App is enabled if that option appears.
6. Tap Add.

Data storage:
- Workout and bodyweight data remains in IndexedDB on that iPhone/browser origin.
- Export backups before clearing Safari website data or changing hosts.
- Hosting only serves the app files; it does not receive training data.

Local testing on a computer:
Run a local web server in this folder, for example: python3 -m http.server 8080
Then open http://localhost:8080. Service workers do not work correctly from file:// URLs.
