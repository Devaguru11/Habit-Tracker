# Habit Tracker

A standalone, browser-based habit tracking app.
No installation. No server. Just open and go.

---

## Overview

Habit Tracker is a single HTML file that runs entirely
in your browser. Track daily habits, visualize progress,
and build streaks — all saved locally on your laptop.

---

## Features

Today
→ Check off habits, view streaks, stat cards
  (daily count, weekly %, best streak, total check-ins)

Analytics
→ 30-day bar chart, per-habit doughnut chart,
  timeline graph, 8-week heatmap

Manage Habits
→ Add habits with custom colors, remove old ones,
  view all-time stats per habit

Weekly Grid
→ Browse past weeks, toggle check-ins in the grid

---

## Getting Started

1. Download habit-tracker.html
2. Open in Chrome, Edge, Firefox, or Safari
3. Check off habits — data saves automatically

---

## Tech Stack

- HTML5, CSS3, Vanilla JavaScript
- Chart.js 4.4.1
- Google Fonts (DM Serif Display + DM Sans)
- localStorage for persistent data

---

## Data & Privacy

All data lives in your browser's localStorage.
Nothing is sent to any server.
To back up: open browser console and run —
  JSON.stringify(localStorage.getItem('habit_app_v2'))

---

## Limitations

- Data is browser-specific, no cross-device sync
- Requires internet on first load (fonts + Chart.js CDN)
- Clearing browser data will erase habit history

---

Built with HTML, CSS, JavaScript & Chart.js
