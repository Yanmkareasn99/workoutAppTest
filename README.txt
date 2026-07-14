WEEKLY WORKOUT TRACKER — iPHONE / iOS VERSION

This package is an installable Progressive Web App (PWA). It behaves like a Home Screen app and keeps workout data in the browser on the device.

FILES TO UPLOAD
- index.html
- app.css
- manifest.webmanifest
- sw.js
- icons/ folder

IMPORTANT
The entire folder must be hosted on an HTTPS website. Do not open index.html directly from the iPhone Files app; offline installation and the service worker will not work from a file:// address.

INSTALL ON IPHONE
1. Upload all files and folders to the same website directory.
2. Open the HTTPS URL in Safari on the iPhone.
3. Tap Safari's Share button.
4. Choose Add to Home Screen.
5. Tap Add.
6. Open Workout from the Home Screen once while online so the complete app is cached.

EASY HOSTING OPTIONS
- GitHub Pages
- Netlify
- Cloudflare Pages
- Any HTTPS web server

DATA
Workout routines and progress are stored locally on the device using browser storage. Use “Export week” inside the app to keep a JSON backup.

UPDATING
When replacing files on the website, change CACHE_NAME in sw.js (for example, from weekly-workout-ios-v1 to weekly-workout-ios-v2) so installed devices download the new app files.


VERSION 2 FEATURES
------------------
- Stopwatch removed; all timers now count down.
- Sets & reps exercises use the rest countdown.
- Timed exercises such as walking and running store a duration.
- Exercise countdown automatically marks a timed exercise complete.
- Existing saved weekly routines are preserved and treated as sets/reps exercises.
