# Reddit + NTA Telegram Notifier (Modern)

Features:
- Monitors configured subreddits for new posts
- Parses the NTA RSS feed for announcements
- Sends rich Telegram notifications via Telegraf
- Persists last-seen state in SQLite (better-sqlite3)
- Configurable poll interval

Quick start:
1. Copy files into a folder.
2. `cp .env.example .env` and fill values.
3. `npm ci`
4. `npm run build`
5. `npm start`

Dev mode: `npm run dev`