# GameDay Planner

A standalone, installable Progressive Web App for organizing a gaming backlog and play schedule.

## Features
- Add, edit, and delete games
- Track Backlog, Scheduled, and Played status
- Set a planned date and optional time
- Platform and notes fields
- Search, filter, and sort
- Local device storage
- Export a JSON backup
- Offline app shell after first load
- Installable on Android through Chrome

## Publish
This app is hosted as its own sub-app under the repository's GitHub Pages site at `/gaming-planner/`. The manifest and service worker are scoped to this folder.

## Android installation
Open the deployed app in Chrome, open the browser menu, and choose **Install app** or **Add to Home screen**.

## Data
Game data stays in the browser's local storage on the device. Use Export to back up the list. Clearing Chrome site data or switching devices will not transfer the list automatically.
