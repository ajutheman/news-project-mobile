# The Profit - Mobile Application

Mobile client for The Profit Malayalam News portal (iOS & Android).

## Architecture
- Framework: Flutter (Dart) or React Native (Expo)
- Backend API: Connects to `https://theprofit.in/api/v1` (served by `news-project-web`)
- Database: Supabase authentication & offline sync (Hive / SQLite)

## Features Planned
- Breaking news push notifications (FCM / APNs)
- Malayalam text shaping and font scaling
- Offline reading for saved articles
- Audio news / text-to-speech player
- Live gold rate and currency widgets

## Git Branching Model
- `main`: Production app store release builds (protected)
- `develop`: Nightly builds and staging integration
- `feature/*`: Specific UI / feature screens
EOF
