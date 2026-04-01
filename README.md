# Shorts Tracker

YouTube Shorts competitor leaderboard. Tracks Shorts-only views across channels and ranks them by views gained over 24h / 7d / 14d / 30d.

## Deploy to Render

1. Push this repo to GitHub
2. Go to [render.com](https://render.com) → New → **Static Site**
3. Connect your GitHub repo
4. Set **Publish Directory** to `public`
5. Hit **Create Static Site**

Your site will be live at `https://shorts-tracker-xxxx.onrender.com`

## Setup

1. Get a free YouTube Data API v3 key from [Google Cloud Console](https://console.cloud.google.com/apis/library/youtube.googleapis.com)
2. Open your site → click ⚙ → paste the API key
3. Add competitor channels by URL or @handle
4. Hit **Refresh All** daily to build view count history
