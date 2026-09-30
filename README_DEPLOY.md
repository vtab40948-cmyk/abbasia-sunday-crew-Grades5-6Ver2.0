# Sunday Crew — Full Firebase App UI Refresh

This package keeps the full Firebase application logic and uses the app-style interface as a presentation layer.

## GitHub Pages root
Upload these files directly to the repository root:

- index.html
- manifest.json
- sw.js
- icon-180.png
- icon-192.png
- icon-512.png
- firestore.rules

## Firebase
Keep the Firebase project and Auth accounts already configured for the app.

## Firestore rules
Deploy `firestore.rules` in Firebase Console → Firestore Database → Rules.

Do not use an open rule such as `allow read, write: if true;`.
