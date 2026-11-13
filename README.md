# MyLearningTracker
This repository is to help me track and organize my learning across a multitude of studies.

A single-page site to log daily study/practice, watch your consistency, and keep resources and recordings organized. Runs entirely in the browser (no build step, no backend).

## Put it on GitHub Pages
1. Create a new GitHub repo (e.g. `learning-tracker`).
2. Upload `index.html` (and this README) to the repo root.
3. Repo **Settings → Pages → Build and deployment**: Source = "Deploy from a branch", Branch = `main`, folder = `/ (root)`. Save.
4. After a minute your site is live at `https://<your-username>.github.io/learning-tracker/`.

## Using it
- **Log**: pick a topic, minutes, and a short note. Tick "Recorded" to drop it into the Content pipeline.
- **Progress**: today / streak / weekly goals per topic, a consistency heatmap, and weekly minutes by topic. Weekly goals and the 4-month date range are editable at the bottom.
- **Resources**: links per topic with todo / doing / done status.
- **Checkpoints**: every 2–4 weeks, record a score or result per topic so improvement is visible.
- **Content**: recorded sessions with tags for Edited, YouTube, Twitch, IG/TikTok.

## Your data
Saved in your browser's local storage, so each device/browser has its own copy. Use **Export backup** (Progress → Settings) regularly, and **Import backup** to move it to another device. You can commit the exported JSON to the repo as a safety copy.
