# 🔥 Firebase Site Starter

> **Launch a beautiful static site in 5 minutes ⚡ — in just 6 easy steps!**

A simple **static landing page template** perfectly configured for **Firebase Hosting**.
Use it as your starting point for:

* 💼 Client marketing pages
* 💡 Quick prototypes
* 🌐 Fast-deploy static sites

---

## 🎁 What's Inside

* ✅ Minimal **HTML/CSS layout** (hero, about, features, contact)
* 📱 **Mobile-friendly** design with editable colors & fonts
* ⚙️ **Firebase CLI scripts** for one-command deploys + local emulation
* ✏️ Placeholder content & clear callouts for easy customization

---

## 🧰 Prerequisites

Before you start, make sure you have:

* 🟢 **Node.js 18+**
* 🔥 **Firebase project** (create one in the [Firebase Console](https://console.firebase.google.com/))
* 🧑‍💻 **Firebase CLI** (install & log in)

If you are on a fresh computer and brand new to the web, follow these quick prep steps:

1. Open a browser and download Node.js from [nodejs.org](https://nodejs.org/). Run the installer and accept the defaults.
2. Visit the [Firebase Console](https://console.firebase.google.com/), sign in with a Google account, and create a new project—no coding required.
3. Install the Firebase CLI by opening the Terminal/PowerShell app and running:

  ```bash
  npm install -g firebase-tools
  firebase login
  ```

The `firebase login` command will open a browser window—just approve access, and you're ready for the next steps.

---

## ⚡ Getting Started (6 Steps, 5 Minutes!)

> Follow these **6 quick steps** to go from zero → live site 🌍

### 1️⃣ Clone this repo

```bash
git clone https://github.com/FrancescoRec/Firebase-Site-Starter.git
cd Firebase-Site-Starter
```

> 💡 **Pro Tip:** Prefer not to use Git commands? Click the green `Code` button on GitHub and choose “Download ZIP,” then extract it locally.
>
> Already comfortable with GitHub? Fork the repo (or create a new one from the ZIP) so you can:
> - 🔄 Track your own version history
> - 💪 Open pull requests for changes
> - 🚀 Hook up GitHub Actions for automated Firebase deploys
>
> Stick with this option only if you want that extra control.

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Connect your Firebase project

```bash
firebase use --add
```

Choose your project and set it as the default.
Optionally, add an alias (`default`, `staging`, `prod`) for easy switching 🔄.

### 4️⃣ Run locally

```bash
npm run dev
```

🔥 Launches a live preview with auto-reload at
👉 [http://localhost:5000/](http://localhost:5000/)

### 5️⃣ Customize your site

- 🖋️ Refresh the **brand name, navigation links, and page copy** in `index.html`.
- 🎨 Tweak the **color and spacing tokens** at the top of `style.css` to match your visual identity.
- 🤖 Want inspiration fast? Drop the markup into your favorite AI assistant for quick headline or layout ideas.
- ⚡ All changes you make to your files will be reflected in real time on localhost. Just save and see your updates instantly!

### 6️⃣ Deploy to production

```bash
npm run deploy
```

Deploys to Firebase Hosting using your `firebase.json` config.
🎉 Boom — your site is live!

## 🗂️ Directory Overview

```
.
├── index.html      # Landing page markup
├── style.css       # Global styles and theme tokens
├── 404.html        # Default Firebase Hosting 404 page
├── firebase.json   # Hosting configuration
├── .firebaserc     # Stores the default Firebase project alias
└── package.json    # NPM scripts + firebase-tools dependency
```

---

🧡 **Done!** You just built and deployed a Firebase site in **5 minutes and 6 steps**.
Now go make it yours 🎉


