# Evently

An event-planning app built with Flutter and Firebase. Users can create, browse, and save events by category.

## Features

- **Authentication**: register, log in, and reset password with Firebase Auth
- **Events**: create events and store them in Cloud Firestore
- **Categories**: filter events (sport, birthday, meeting, gaming, workshop, book club, exhibition, holiday, eating)
- **Favorites**: add events to a favorites tab
- **Profile**: switch language and theme
- **Localization**: English and Arabic
- **Themes**: light and dark mode
- **Onboarding and native splash screen**

## Tech Stack

- Flutter / Dart
- Firebase Auth & Cloud Firestore
- Provider (state management)
- flutter_localizations / intl
- flutter_native_splash, introduction_screen

## Project Structure

```
lib/
├── custom_widgets/      # Reusable widgets (buttons, text fields, dialogs, ...)
├── l10n/                # Localization files (en, ar)
├── model/               # Data models (AppUser, Event)
├── on_boarding_screen/  # Onboarding flow
├── provider/            # Theme, language, user, and events providers
├── ui/
│   ├── auth/            # Login, register, forget password
│   └── home_screen/     # Home, add event, and tabs (home, map, favourite, profile)
├── utils/               # Colors, text styles, theme, asset paths
├── firebase_utils.dart  # Firestore helpers
└── main.dart
```

## Getting Started

```bash
git clone https://github.com/mohamedaboughonema/evently.git
cd evently
flutter pub get
flutter run
```

## Roadmap

- [ ] Map tab (show events on a map)
