## Firebase Site Starter

Static landing page template configured for Firebase Hosting. Use it as the base for new marketing sites, client projects, or quick prototypes that you deploy with the Firebase CLI.

### What's Included
- Minimal HTML/CSS layout with hero, about, features, and contact sections
- Mobile-friendly design with configurable colours and typography
- Firebase CLI scripts for local emulation and one-command deploys
- Placeholder content and callouts that highlight where to customize

### Prerequisites
- Node.js 18 or newer
- Firebase project (create one in the [Firebase console](https://console.firebase.google.com/))
- Firebase CLI authenticated with your Google account (`npm run login`)

### Getting Started
1. **Install dependencies**
   ```bash
   npm install
   ```
2. **Connect a Firebase project**
   ```bash
   firebase use --add
   ```
   Select your project and set it as the default. This updates `.firebaserc`.
3. **Run locally**
   ```bash
   npm run dev
   ```
   The hosting emulator serves the site with live reload.
4. **Deploy to production**
   ```bash
   npm run deploy
   ```
   Deploys only the Hosting target defined in `firebase.json`.

### Customize for Your Project
- Update brand name, links, and copy in `index.html`
- Swap accent colours or spacing tokens at the top of `style.css`
- Add sections by duplicating the existing ones—everything shares consistent container styles
- Replace the placeholder form with your preferred provider (Formspark, Netlify Forms, etc.)

### Directory Overview
```
.
├── index.html      # Landing page markup
├── style.css       # Global styles and theme tokens
├── 404.html        # Default Firebase Hosting 404 page
├── firebase.json   # Hosting configuration (public directory, ignore rules)
├── .firebaserc     # Stores the default Firebase project alias
└── package.json    # NPM scripts and firebase-tools dependency
```

### Next Steps
- Add analytics, fonts, or component libraries specific to your needs
- Configure additional Firebase products (Functions, Firestore, etc.) with `firebase init`
- Commit this starter to a new repository to clone for each client or brand

