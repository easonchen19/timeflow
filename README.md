# Timeflow ⏱

A minimal, Notion-style activity tracker. Paint your week in 30-minute strokes, break goals into tasks, and see where your time actually goes.

**Features**

- Weekly calendar with 30-min slots — drag to paint activities in color-coded categories
- Goals with sub-tasks: click a task, paint it onto the grid, hours are tracked automatically
- Measurable goals: numeric targets (e.g. 0/50 people), deadlines, and automatic on-track / behind pace
- Analytics: time by activity, by day, goal progress, and insights
- Light/dark theme, subtle sounds, confetti on completed goals
- All data stays in your browser (localStorage) — export/import JSON backups from the Data menu

**Google Calendar sync**

The 📅 Sync button connects your own Google Calendar with Google's official sign-in. Events are fetched directly into your browser (read-only scope) and merged onto the grid — nothing touches a server, and synced meetings only fill empty slots so your own edits always win.

To enable it on your own deployment: create an OAuth **Web application** client ID in [Google Cloud console](https://console.cloud.google.com/apis/credentials) with your site's URL as an authorized JavaScript origin, then set `GCAL_CLIENT_ID` at the top of the script in `index.html`.

**Run it**

It's a single self-contained `index.html` — open it in a browser, or deploy anywhere static.

Built with Claude.
