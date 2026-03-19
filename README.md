# PATTA GHOBI — PWA Install Guide

## Deploy to Vercel (FREE, ~5 minutes)

### Step 1 — Upload to GitHub
1. Go to https://github.com and create a free account if you don't have one
2. Click the **+** button → **New repository**
3. Name it `patta-ghobi`, set to Public, click **Create repository**
4. Click **uploading an existing file**
5. Drag ALL these files into the upload area:
   - index.html
   - manifest.json
   - sw.js
   - vercel.json
   - icon-192.png
   - icon-512.png
6. Click **Commit changes**

### Step 2 — Deploy on Vercel
1. Go to https://vercel.com and sign in with your GitHub account
2. Click **Add New → Project**
3. Find `patta-ghobi` and click **Import**
4. Click **Deploy** (no settings needed)
5. Wait ~30 seconds — you'll get a link like `patta-ghobi.vercel.app`

### Step 3 — Install on iPhone
1. Open the Vercel link in **Safari** (must be Safari, not Chrome)
2. Tap the **Share** button (box with arrow pointing up)
3. Scroll down and tap **"Add to Home Screen"**
4. Tap **Add**
5. The PATTA GHOBI icon appears on your home screen!
6. Open it — it runs fullscreen like a real app ✅

---

## Features
- ⚡ Dashboard with today's stats
- 🏋️ Workout logging with per-exercise progress graphs
- 🥗 Nutrition tracking with AI food photo analysis
- 📈 Weight progress chart with goal projection
- 🤖 AI Coach — personalized reports + chat (powered by Claude)
- 💾 All data saved on your phone (localStorage)

## Notes
- The AI features use Claude API and require internet
- All workout/food/weight data is saved locally on your device
- Works offline for viewing data (AI chat needs internet)
