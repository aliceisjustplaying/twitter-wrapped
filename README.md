# Twitter Wrapped 2025

A Spotify Wrapped-style visualization of your Twitter/X archive data.

## Setup

1. Export your Twitter archive from Twitter/X settings
2. Place the `data/` folder from your archive in this directory
3. Install dependencies and run:

```bash
bun install
bun run dev
```

4. Open http://localhost:5173

## How it works

- `analyze.js` - Parses your Twitter archive and extracts 2025 stats
- `index.html` - Single-page visualization with animations and charts

## Features

- Total tweets, likes, and engagement stats
- Monthly/weekly/hourly activity charts
- Top mentions ("ride-or-dies")
- Word cloud and emoji usage
- Viral tweet highlight
- Posting streak tracking
- Mobile-optimized slide layout
