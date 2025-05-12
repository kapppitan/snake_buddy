# 🐍 Snake Buddy

**Snake Buddy** is a mobile application designed to help users identify snakes with ease. Whether you're a herpetologist, a nature enthusiast, or just curious, Snake Buddy provides detailed information about various snake species.

---

## 🌟 Features

- **Snake Identification**:
  - Upload an image from your device.
  - Scan directly using your camera.
- **Snake Library**:
  - Access a library of up to 20 Philippine snake species.
  - View detailed information about each species, including images, descriptions, and conservation status.

---

## 📋 Requirements

To run this project, ensure you have the following installed on your system:

1. **Flutter SDK**  
   - Install Flutter from the [official website](https://flutter.dev/docs/get-started/install).
   - Ensure the Flutter version matches the one used in this project (check the `pubspec.yaml` file for compatibility).

2. **Dart SDK**  
   - Dart is included with Flutter, but ensure it's properly installed and configured.

3. **Android Studio or Xcode**  
   - For Android: Install [Android Studio](https://developer.android.com/studio) and set up an emulator or connect a physical device.  
   - For iOS: Install [Xcode](https://developer.apple.com/xcode/) (macOS only).

4. **Google API Key**  
   - Obtain a Google API key from the [Google Cloud Console](https://console.cloud.google.com/).  
   - Add the key to a file named `api_keys.dart` in the `lib/helper/` directory:
     ```dart
     const String googleApiKey = "your_google_api_key_here";
     ```

5. **Dependencies**  
   - Install project dependencies by running:
     ```bash
     flutter pub get
     ```

6. **Device or Emulator**  
   - A physical device or emulator must be set up to run the app.

---

## 📂 Getting Started

1. Install Flutter dependencies:
   ```bash
   flutter pub get
   ```

2. Run the Flutter application through `main.dart`:
   ```bash
   flutter run
   ```

3. If you encounter issues, ensure your environment is properly configured by running:
   ```bash
   flutter doctor
   ```