# Iron & Thali — Deploy to GitHub Pages

You already have a GitHub account, so this takes about 5 minutes.

## 1. Create the repo
1. Go to github.com → **New repository**
2. Name it e.g. `iron-thali` → Public → **Create repository**

## 2. Upload the files
On the new repo page, click **"uploading an existing file"** and drag in all 5 items from this folder:
- `index.html`
- `manifest.json`
- `service-worker.js`
- `icons/icon-192.png`
- `icons/icon-512.png`

(Keep the `icons` folder structure — GitHub's uploader preserves folders if you drag the whole `icons` folder in.)

Commit the files.

## 3. Turn on GitHub Pages
1. In the repo, go to **Settings → Pages**
2. Under "Build and deployment", set **Source: Deploy from a branch**
3. Branch: `main`, folder: `/ (root)` → **Save**
4. Wait ~1 minute, then refresh — GitHub gives you a live URL like:
   `https://<your-username>.github.io/iron-thali/`

## 4. Install it on your phone
1. Open that URL in your phone's browser (Chrome on Android, Safari on iOS)
2. You'll see an **"Install App"** banner — tap it (Android/Chrome), or
   on iOS: **Share → Add to Home Screen**
3. It now opens full-screen with its own icon, works offline, and saves
   your logs, weights, and checkmarks directly on your phone (no account,
   no internet needed after first load).

## Notes
- All your data (meals logged, workout checkmarks, weight history) is stored
  locally on that phone/browser only — it won't sync across devices.
  If you want it on two phones, you'd log separately on each, or we can
  add a simple cloud sync later.
- To update the plan later (new week 5-8 progressions, adjusted meals),
  just edit `index.html` and re-upload — GitHub Pages updates automatically.
