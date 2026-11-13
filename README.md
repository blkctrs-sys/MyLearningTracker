# MyLearningTracker

**Live site:** https://blkctrs-sys.github.io/MyLearningTracker/

A personal learning tracker for keeping several skills moving at once. Log each study or practice session, see your streaks and weekly progress per topic, keep a curated list of learning resources, record checkpoints to measure improvement, and track which practice sessions you've recorded and posted as content.

It's a single HTML file with no sign-up, no server and no build step. Everything is saved in your own browser.

**Topics it's set up for right now:** CompTIA A+, neo soul (Pickup Music), figure/character drawing, Blender character rigging, and Unreal Engine game development. The topics live in `index.html` (the `TOPICS` list), so you can swap in your own.

## Host your own copy (GitHub Pages)
1. Fork this repo, or create a new one (e.g. `learning-tracker`) and upload `index.html` (and this README) to the repo root.
2. Repo **Settings → Pages → Build and deployment**: Source = "Deploy from a branch", Branch = `main`, folder = `/ (root)`. Save.
3. After a minute your site is live at `https://<your-username>.github.io/learning-tracker/`.

## Using it
- **Log**: pick a topic, minutes, and a short note. Tick "Recorded" to drop it into the Content pipeline.
- **Progress**: today / streak / weekly goals per topic, a consistency heatmap, and weekly minutes by topic. Weekly goals and the 4-month date range are editable at the bottom.
- **Resources**: a starter list of courses, channels and references for each topic, plus your own links. Tap the status button to cycle todo / doing / done.
- **Notes**: a separate notebook for each topic. Pick a topic, write a note, and edit or delete it later.
- **Checkpoints**: every 2–4 weeks, record a score or result per topic so improvement is visible.
- **Content**: recorded sessions with tags for Edited, YouTube, Twitch, IG/TikTok.

## Your data
Saved in your browser's local storage, so each device/browser has its own copy. Use **Export backup** (Progress → Settings) regularly, and **Import backup** to move it to another device. You can commit the exported JSON to the repo as a safety copy.
