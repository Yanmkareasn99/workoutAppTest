EXERCISE LIBRARY + GUIDE — VERSION 5

This version adds a searchable exercise library to the weekly iPhone workout tracker while preserving all earlier routines and settings.

NEW FEATURES
- Autocomplete while typing an exercise name.
- 800+ exercise records load from Free Exercise DB when online and are saved locally for later use.
- Search by exercise name, target muscle, equipment, level, or category.
- Automatic exercise-type suggestion:
  • Walking, running, cycling, stretching, planks, and similar activities use timed duration.
  • Strength exercises use sets and reps.
- Suggested starting duration for timed exercises.
- Exercise preview before adding.
- Exercise thumbnails in the daily routine.
- Full exercise guide with step-by-step instructions and up to two pictures.
- Creative Commons video lookup through Wikimedia Commons.
- Each video shows a link to its source and file-specific license information.
- Custom exercise names still work when no library match is selected.

FREE CONTENT SOURCES
Exercise data and pictures:
https://github.com/yuhonas/free-exercise-db
The project describes its dataset as public domain under the Unlicense.

Video demonstrations:
https://commons.wikimedia.org/
Each Wikimedia file has its own license and attribution page. The app links to that page.

ONLINE AND OFFLINE BEHAVIOR
- The app shell and weekly routines continue to work offline.
- A starter library is built into index.html, so autocomplete works immediately.
- When online, the complete exercise library downloads and is stored in browser storage.
- Exercise pictures already viewed can be reused from the service-worker cache.
- Videos normally require an internet connection and are intentionally not cached because they may be large.

FILES TO UPLOAD TO VERCEL
- index.html
- app.css
- manifest.webmanifest
- sw.js
- icons/ folder

DEPLOYMENT
1. Replace the files in the existing Vercel project with this package.
2. Deploy the project.
3. Open the live site once in Safari and refresh it.
4. Close and reopen the Home Screen app.
5. The service-worker cache name is now weekly-workout-ios-v5-exercise-library.

IPHONE INSTALLATION
1. Open the HTTPS Vercel URL in Safari.
2. Tap Share.
3. Choose Add to Home Screen.
4. Tap Add.

DATA AND PRIVACY
Weekly routines, progress, settings, the downloaded exercise catalog, and video lookup cache are stored in the browser on the device. Use Export week for a JSON backup of the workout plan.

SAFETY
The instructions are general educational guides. Stop if an exercise causes sharp pain, dizziness, or unusual discomfort, and seek qualified advice when needed.
