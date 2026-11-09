# MyApplication

A simple Android app built with Kotlin and Jetpack Compose (Material 3).

## Features
- **Login screen** – email and password fields, with Login and Sign Up buttons.
- **Sign up screen** – first name, last name, email, password and confirm password fields:
  - hint when the password is shorter than 6 characters
  - error when the passwords don't match
  - "Show password" toggle
  - "I agree to the Terms of Use" checkbox
  - "Create account" button enabled only when every field is filled, the passwords match and the terms are accepted

## Requirements
- Android Studio (Ladybug or newer)
- JDK 17
- Min SDK 24, target SDK 35

## Run
1. Clone the repository.
2. Open the folder in Android Studio.
3. Let Gradle sync, then press **Run**.

Or from the command line:
```bash
./gradlew assembleDebug
```
