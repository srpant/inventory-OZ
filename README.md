# Chef Santosh — Inventory System

A Progressive Web App (PWA) for kitchen ingredient inventory management.

## 🌐 Live App
**https://YOUR-USERNAME.github.io/chef-santosh-inventory/**

> Replace `YOUR-USERNAME` with your GitHub username after deploying.

## 📲 Install as App (Android / Samsung Browser)
1. Open the link above in **Samsung Internet** or **Chrome**
2. Tap the **⋮ menu** → **"Add to Home Screen"** or **"Install App"**
3. The app installs like a native app — works offline too!

## ✨ Features
- **Enter Inventory** — Type ingredient name, autocomplete from database, enter qty → saves instantly
- **Database** — Full ingredient database with price, unit, last month / current month tracking
- **Log** — Grouped by item (same item within 5 days = summed). Edit or delete groups.
- **Import / Export** — Excel (.xlsx) import & export with grouped summary + raw sheets

## 🗂 Files
| File | Purpose |
|------|---------|
| `index.html` | Main app (single file, no build needed) |
| `manifest.json` | PWA manifest — enables Install prompt |
| `sw.js` | Service Worker — offline support |
| `icon-192.png` | App icon (192×192) |
| `icon-512.png` | App icon (512×512) |
| `icon-180.png` | Apple touch icon |
| `favicon.ico` | Browser tab icon |

## 🚀 Deploy to GitHub Pages
1. Create a new GitHub repository (e.g. `chef-santosh-inventory`)
2. Upload **all files** from this folder
3. Go to **Settings → Pages → Source → main branch / root**
4. Save — your app is live in ~1 minute!

## 📊 Excel Import Format
Columns expected: `Name`, `Unit`, `Brand`, `Price/Unit`, `Last Month`, `Current Month`
