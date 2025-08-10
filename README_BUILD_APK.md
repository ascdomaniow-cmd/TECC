# Build Android APK
## Local
flutter pub get
flutter build apk --release
APK: build/app/outputs/flutter-apk/app-release.apk

## GitHub Actions
- Push the project (folder tecc_app) to a GitHub repo.
- Workflow `.github/workflows/android_build.yml` will build release APK.
- Download artifact `app-release-apk` from Actions run.
