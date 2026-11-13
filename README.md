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
- **Log**
  - **Focus session:** pick a topic and a length (15/25/30/45 min) and hit Start. When time's up you get a sound and, if allowed, a notification. Then log the session with one thing you learned and your next step, and take a 5 or 15 minute break.
  - **What next?** suggests the topic that's furthest behind its weekly goal (it nudges you to switch if you just did that topic). It also shows the next step you planned last time.
  - **Log a session manually** for practice done away from the timer.
- **Progress**: today / streak / weekly goals per topic, a consistency heatmap, and weekly minutes by topic. Weekly goals and the date range are editable in Settings.
- **Resources**: a starter list of courses, channels and references for each topic, plus your own links. Tap the status button to cycle todo / doing / done.
- **Notes**: a separate notebook for each topic. "One thing you learned" from a session lands here too. Notes come back for **review** after 1, 3, 7, 21 and 60 days. Give a note a title ending in "?" and it becomes a quiz question with a hidden answer.
- **Checkpoints**: every 2–4 weeks, record a score or result per topic so improvement is visible.
- **Content**: recorded sessions with tags for Edited, YouTube, Twitch, IG/TikTok.

## Your data
Saved in your browser. To back it up and use it on several devices, turn on **GitHub sync** (Progress → GitHub sync). It saves a `data.json` file to a **private** repo you create, using a fine-grained token that can only access that repo. The token stays in your browser and is never included in your data. If two devices change things before syncing, both sets of changes are kept.

Without sync, use **Export backup** / **Import backup** (Progress → Settings).
