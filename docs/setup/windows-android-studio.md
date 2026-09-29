# Windows Android Development Setup

This checklist validates the local development environment for Android training on Windows.

## Required Tools

- Android Studio
- IntelliJ IDEA Community or Ultimate
- Git
- A GitHub account connected to Git
- Android SDK installed through Android Studio
- Android emulator or physical Android device

## Android Studio Checks

1. Open Android Studio.
2. Confirm the Android SDK is installed.
3. Confirm at least one emulator image is available, or prepare a physical device with USB debugging.
4. Create a default Android project using Kotlin and Jetpack Compose.
5. Run the app and confirm it opens on an emulator or device.

## Git Checks

Run these checks in a terminal:

```powershell
git --version
git config --global user.name
git config --global user.email
```

The name and email should match the identity you want in GitHub commits.

## First Validation Result

Record the result in `progress/learning-log.md`:

- Android Studio version
- Kotlin or Gradle version shown by the first project
- Emulator or device used
- Any error messages and how they were solved
