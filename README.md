# FOCUS OS

A personal productivity dashboard for daily routines, study, creative work, fitness, meals, sleep and focused work.

## Current features
- Live clock and daily progress dashboard
- Editable daily schedule with add, delete and reset
- Daily task completion tracking
- Focus timer with 25 / 50 / 90 minute presets
- Daily notes
- Seven-day progress insights
- Export and import JSON backups
- Local device storage
- Installable PWA with offline caching after first load
- Android Studio project and automated debug APK workflow

## Web app
GitHub Pages can host this project for free. Open **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, then save. Open the published HTTPS URL on your phone and choose **Add to Home Screen**.

## Android APK
The Android project is in `android/`. A GitHub Actions workflow builds a debug APK when the Android source or workflow changes. See the Actions tab and download the `focusos-debug-apk` artifact after a successful run.

## Important limitations
The web app is a Progressive Web App. It cannot guarantee background alarms or block other apps. Browser timers and notifications may be suspended by the operating system. The Android APK currently wraps the web interface; native alarm scheduling and app blocking are not yet implemented. Use the phone's built-in Clock app for critical alarms.

## Privacy
Routine, notes and progress are stored locally on the device. There is currently no account or cloud sync.

## Status
Working MVP in development.