# MENTALIST OS

A mobile-first, installable web app for study, fitness, mindset and competitive preparation.

## Included
- Daily dashboard, editable missions, XP and ranks
- Class 12 subject/chapter progress and study-session log
- Fitness sessions, distance, duration and recovery notes
- Habit tracker, reflection and sleep log
- NDA / competitive practice, accuracy and recurring mistake topics
- 7-day report and study-hours chart
- In-app reminder planner and optional browser notifications
- Local browser storage, JSON export and import
- Offline cache and installable PWA support

## Run locally
For a quick preview, open `index.html` in a browser. Data saving works, but PWA installation and offline service-worker features require HTTPS or localhost.

## Put it online for free (recommended)
1. Create a GitHub account if you do not have one.
2. Create a new public repository named `mentalist-os`.
3. Upload all files in this folder to the repository root.
4. Open repository **Settings → Pages**.
5. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. Wait for the Pages URL to appear. Open it in Chrome on your Android phone.
7. In Chrome, tap **⋮ → Add to Home screen** or **Install app**.

Alternative: drag this folder into a new Netlify site deployment. Use the HTTPS URL it provides.

## Data and privacy
All tracker records are saved in local browser storage on the device/browser where the app is used. There is no account or cloud sync. Export a JSON backup regularly, especially before clearing browser data or changing phones.

## Reminder limitation
In this version, reminders are checked while the app is open. Browser notification support and background delivery vary by device/browser. It does not promise reliable alarms when the app is closed.

## XP
XP is awarded for logged study time, training duration, competitive questions and completed habits. XP is a motivational indicator, not a measure of personal worth or actual exam readiness.
