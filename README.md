# The Productivity Chain

A daily productivity tracker with Google Sign-In and Firebase sync. Track your productivity levels across devices with a visual calendar interface.

## Features

- 🔐 Google Authentication
- ☁️ Cloud sync via Firebase
- 📅 Visual calendar tracking (Sept 2025 - June 2026)
- 🎨 4-level productivity status system
- 📱 Responsive design

## Productivity Levels

- **Dark Green**: Maximum productivity
- **Light Green**: Good day, but not best
- **Light Red**: Low output day
- **Deep Red**: Wasted day
- **Neutral**: Clear status

## Setup

1. Clone the repository
2. Update the Firebase configuration in `index.html` with your own credentials:

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID",
};
```

3. Open `index.html` directly in your browser

## Security Note

Firebase client-side API keys are safe to expose in public code as they're meant for client apps. However, ensure your Firebase security rules are properly configured to protect your data.

## Tech Stack

- HTML5
- Tailwind CSS
- Firebase (Auth + Firestore)
- Vanilla JavaScript (ES6 Modules)
