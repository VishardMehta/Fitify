# Fitify 🏋️‍♂️

A cross-platform fitness application built with Flutter.

## Platforms

| Platform | Status |
|----------|--------|
| 📱 Android | ✅ |
| 🍎 iOS | ✅ |
| 🌐 Web | ✅ |
| 🖥️ macOS | ✅ |
| 🐧 Linux | ✅ |
| 🪟 Windows | ✅ |

## Tech Stack

- **Framework:** Flutter 3.41.5 (Dart 3.11.3)
- **Architecture:** Multi-platform from a single codebase
- **Package:** `com.vishard.fitify`

## Getting Started

### Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (3.41.5+)
- [Android Studio](https://developer.android.com/studio) (for Android)
- [Xcode](https://developer.apple.com/xcode/) (for iOS/macOS)
- [Chrome](https://www.google.com/chrome/) (for Web)

### Run

```bash
# Install dependencies
flutter pub get

# Run on Web
flutter run -d chrome

# Run on macOS
flutter run -d macos

# Run on iOS Simulator
flutter run -d <simulator-id>

# Run on Android
flutter run -d <device-id>
```

### Build

```bash
# Build APK (Android)
flutter build apk

# Build iOS
flutter build ios

# Build Web
flutter build web

# Build macOS
flutter build macos
```

## Project Structure

```
lib/
└── main.dart          # App entry point

test/
└── widget_test.dart   # Widget tests

android/               # Android platform config
ios/                   # iOS platform config
web/                   # Web platform config
macos/                 # macOS platform config
linux/                 # Linux platform config
windows/               # Windows platform config
```

## License

This project is private.
