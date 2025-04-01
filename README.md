# VibeJournal

*Your music, your memories — one season at a time.*

---

## Overview

VibeJournal is a personal Spotify companion that automatically generates playlists based on your top songs for a given timeframe. Whether it's every season, month, or quarter, it builds a music archive that reflects how you felt, what you loved, and who you were — all through your listening history.

---

## Features

- 🔁 **Custom Timeframe Tracking**: Generate playlists seasonally, monthly, or on your own schedule
- 🎧 **Spotify-Integrated Playback**: Uses your real listening data to build personalized playlists
- ✨ **AI-Powered Titles & Descriptions**: OpenAI generates poetic playlist names and summaries based on your vibe
- 📬 **Email Wrapped Summary**: Sends you a digest of your top artists, genres, mood, and “High Lyric of the Season”
- 🧠 **Lyrics + GPT Analysis**: Extracts lyrics from your top songs and uses GPT to pick one line that captures the essence of your season
- 📊 **Listening Insights**: Visualize how your taste evolves over time
- 📁 **Personal Music Archive**: Saves and stores listening snapshots to build your musical diary

---

## Usage Flow

1. **Connect Spotify**: Authenticate with your Spotify account
2. **Choose Timeframe**: Set your season, month, or custom window
3. **Generate Playlist**: VibeJournal fetches your top tracks and builds a playlist
4. **AI Enhancements**: GPT adds a creative title, description, and picks a "high lyric"
5. **Receive Email Summary**: A personal digest of your listening journey is sent to your inbox
6. **Repeat**: Come back next season and watch your music story unfold

---

## Tech Stack

### Frontend
- Next.js 14
- TypeScript
- Tailwind CSS
- Framer Motion

### Backend
- Node.js or Python
- Spotify Web API
- Genius API 
- OpenAI API (or Gemini API)
- Nodemailer / SendGrid (email delivery)
- Cron jobs or GitHub Actions for scheduling
- Firebase / PostgreSQL for data storage


