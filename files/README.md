# Household Ledger

A simple weekly budgeting app — recurring bills (weekly, biweekly, or any interval you choose), multiple paychecks, a wish list, and month/year totals by category. No build step, no server — it's a handful of static files.

## 1. Put it on GitHub

1. Go to github.com and create a new repository (e.g. `household-ledger`). Public is fine — nothing you type into the app ever leaves your phone.
2. On the repo's main page, click **Add file → Upload files**.
3. Drag in all six files from this folder: `index.html`, `manifest.json`, `service-worker.js`, `icon-192.png`, `icon-512.png`, `icon-512-maskable.png`.
4. Click **Commit changes**.

## 2. Turn on GitHub Pages

1. In the repo, go to **Settings → Pages**.
2. Under "Build and deployment," set **Source** to "Deploy from a branch."
3. Set **Branch** to `main` and the folder to `/ (root)`, then **Save**.
4. GitHub will give you a URL that looks like `https://your-username.github.io/household-ledger/`. It usually takes a minute or two to go live.

## 3. Add it to your phone's home screen

**iPhone (Safari):** open the URL → tap the Share icon → **Add to Home Screen**.

**Android (Chrome):** open the URL → tap the ⋮ menu → **Install app** (or **Add to Home screen**).

Once added, it opens full-screen with its own icon, like a regular app.

## About your data

Everything you enter — bills, paychecks, wish list, past weeks — is saved directly in your phone's browser storage. It never gets sent anywhere, and it isn't tied to your GitHub account. That also means:

- It's specific to that one phone/browser. It won't show up if you open the same link on another device.
- Clearing your browser's site data/cache for this app would erase it, so avoid that.
- If you want a backup or want to move it to a new phone later, just ask and a simple export/import feature can be added.

## Updating it later

If you (or I) ever tweak the app, just re-upload the changed files to the same GitHub repo (Add file → Upload files, overwrite). Your saved data stays put since it lives in the browser, not in the code.
