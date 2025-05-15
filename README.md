# Flutter Firebase Phone Authentication

A modern Flutter application demonstrating phone number authentication using Firebase Authentication. This project provides a simple and secure way to implement phone number verification in your Flutter applications.

## Features

- Phone number authentication using Firebase
- Clean and intuitive user interface
- Real-time verification code handling
- Secure authentication flow
- Cross-platform support (iOS and Android)

## Prerequisites

Before you begin, ensure you have the following installed:

- [Flutter](https://flutter.dev/docs/get-started/install) (latest version)
- [Android Studio](https://developer.android.com/studio) or [VS Code](https://code.visualstudio.com/)
- [Firebase CLI](https://firebase.google.com/docs/cli) (for Firebase configuration)

## Getting Started

### 1. Clone the Repository

```bash
git clone <repository-url>
cd phoneAuth
```

### 2. Firebase Setup

1. Create a new Firebase project in the [Firebase Console](https://console.firebase.google.com/)
2. Enable Phone Authentication in the Firebase Console:
   - Go to Authentication > Sign-in method
   - Enable Phone Number sign-in
3. Add your Android app to Firebase:
   - Use your app's package name
   - Download the `google-services.json` file
   - Place it in the `android/app` directory
4. For iOS setup (optional):
   - Add iOS app in Firebase Console
   - Download `GoogleService-Info.plist`
   - Place it in the `ios/Runner` directory

### 3. Install Dependencies

```bash
flutter pub get
```

### 4. Run the App

```bash
flutter run
```

## Project Structure

```
lib/
├── screens/       # Contains all screen widgets
├── services/      # Firebase and other services
├── widgets/       # Reusable widgets
└── main.dart      # Entry point of the application
```

## Usage

1. Launch the app
2. Enter your phone number with country code
3. Receive verification code via SMS
4. Enter the verification code
5. Access the authenticated section of the app

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Resources

- [Flutter Documentation](https://flutter.dev/docs)
- [Firebase Documentation](https://firebase.google.com/docs)
- [Firebase Phone Auth Guide](https://firebase.google.com/docs/auth/flutter/phone-auth)
- Video Tutorial: [How to implement Phone Authentication](https://youtu.be/RvocbCaGzlM)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
