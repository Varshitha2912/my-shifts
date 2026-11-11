# My Shifts

A free web app for people who work shifts at more than one job. Enter each shift once and it works out the rest:

- **Today**: your next shift with a countdown, today's pay against your daily goal, and this week's progress
- **Week**: a roster that draws every shift at its real time, so clashes and free gaps (gym time!) are obvious
- **History**: pay per week against your goal, best week, missed shifts, and which job pays you the most
- **Reminders**: put all your upcoming shifts in your phone calendar with one tap, with an alert before each one
- **Gym**: plan sessions between shifts, or log one with a single tap
- **Works offline** and can be added to your home screen like an app

Finished shifts are counted as worked automatically, so you only need to open a shift if you missed it or it was cancelled.

## Your data stays on your phone

There are no accounts and no server. Everything is saved in the browser on the device you use. Anyone who opens the link gets their own empty copy. They set their own jobs and rates, and nobody can see anyone else's shifts.

To move to a new phone, or to be safe if you clear your browser, use **Settings → Download backup**, then **Restore from a backup** on the new device. **Export for Excel or Google Sheets** gives you a CSV of every shift.

## Put it online with GitHub Pages (free, about 5 minutes)

1. Sign in at [github.com](https://github.com) (or create a free account).
2. Click **+** (top right) → **New repository**. Name it `my-shifts`, keep it **Public**, and click **Create repository**.
3. On the new repository page, click **uploading an existing file**.
4. Drag in everything from this folder: `index.html`, `manifest.webmanifest`, `sw.js`, `README.md` and the `icons` folder. Click **Commit changes**.
5. Go to **Settings** → **Pages**. Under **Branch**, choose `main` and `/ (root)`, then click **Save**.
6. Wait a minute and refresh. Your app is at `https://YOUR-USERNAME.github.io/my-shifts/`

On your phone, open that link and add it to your home screen:
- **iPhone:** open it in Safari, tap **Share**, then **Add to Home Screen**.
- **Android:** open it in Chrome, tap **⋮**, then **Install app** or **Add to home screen**.

Share the same link with anyone else who wants to use it.

## Updating the app

Replace `index.html` in the repository with a new version. Phones pick up the update the next time the app is opened with an internet connection. Your shifts are not affected.

## Files

| File | What it does |
|---|---|
| `index.html` | The whole app |
| `manifest.webmanifest` | Lets phones install it with a name and icon |
| `sw.js` | Keeps it working with no signal |
| `icons/` | Home screen icons |
