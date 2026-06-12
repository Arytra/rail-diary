# RailDiary 🚂

A personal Indian Railways journey log. Built as a single HTML file — no framework, no server.

## How it works
- **Hosted** on GitHub Pages (this repo)
- **Data** stored in a separate private repo (`rail-diary-data`) as a JSON file
- **Route fetch** pulls intermediate stations from erail.in by train number

## Setup
1. Go to [github.com/settings/tokens/new](https://github.com/settings/tokens/new)
2. Create a classic token with `repo` scope
3. Open the app URL, paste the token once
4. Token is saved in your browser — no need to re-enter

## Features
- Log journeys with train number, name, route, class, distance, notes
- Auto-fetch full route (all intermediate stations) by train number
- Stats dashboard — total rides, total km, class breakdown
- Searchable journey list with stop-by-stop route view
- Syncs across all devices via GitHub
