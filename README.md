# ⚙ WheelTracker PWA

Options income tracker for Covered Calls, Cash-Secured Puts & Wheel Strategy.
Works as a native-feeling iPhone app — **100% free, no subscription, data stays on your device.**

---

## 📲 How to Install on iPhone (Free)

### Option A — GitHub Pages (Recommended, 5 min setup)

1. Create a free account at **github.com**
2. Click **+** → **New repository** → name it `wheeltracker` → set to **Public**
3. Upload these 4 files: `index.html`, `manifest.json`, `sw.js`, `icon-192.png`
4. Go to **Settings** → **Pages** → Source: **main branch** → Save
5. Your app is live at: `https://YOUR-USERNAME.github.io/wheeltracker`
6. On iPhone: open that URL in **Safari** → tap **Share** → **Add to Home Screen**
7. Done! Tap the icon — it opens like a native app ✅

### Option B — Netlify (Drag & drop, 2 min)

1. Go to **netlify.com** → Sign up free
2. Drag your folder to the deploy area
3. Get your URL instantly → open in Safari → Add to Home Screen

### Option C — Vercel

1. Go to **vercel.com** → Sign up free with GitHub
2. Import repository or drag folder
3. Deploy → same iPhone install steps

---

## 🔄 Syncing Data Between Devices (Free)

Since data lives in your browser's localStorage, use the **Export/Import** feature:

1. **Settings** → **Export as JSON** → save file to iCloud Drive or Google Drive
2. On another device → **Settings** → **Import JSON Backup**

This works as your free "cloud sync."

---

## 📁 Files

| File | Purpose |
|------|---------|
| `index.html` | The entire app (self-contained) |
| `manifest.json` | Makes it installable as a PWA |
| `sw.js` | Service worker — enables offline use |
| `icon-192.png` | App icon (192×192) |
| `icon-512.png` | App icon (512×512) |

---

## ✨ Features

- **Single entry** — log a trade once, it auto-appears in CC/CSP/Wheel views
- **Dashboard** — YTD P&L, win rate, monthly breakdown, year-over-year
- **Offline** — works without internet after first load
- **Export** — JSON backup + CSV for spreadsheets
- **Import** — restore from backup anytime
- **Private** — all data stays on your device

---

## 🆓 Totally Free Stack

- Hosting: GitHub Pages / Netlify / Vercel
- Storage: Browser localStorage
- Fonts: Google Fonts (free)
- No backend, no database, no account needed
