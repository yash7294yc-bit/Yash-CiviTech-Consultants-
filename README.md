# Yash CiviTech Consultants

Android application for civil engineering knowledge, information, career opportunities, construction methodology, latest technology, IS Codes, field/lab practicals and tests, and infrastructure projects.

## Build without Android Studio

This project includes a GitHub Actions workflow at `.github/workflows/build-apk.yml`.

1. Upload the contents of this project to a GitHub repository.
2. Open the repository's **Actions** tab.
3. Select **Build Android APK**.
4. Tap **Run workflow**.
5. After the workflow succeeds, open the run and download the `YashCiviTechConsultants-debug-apk` artifact.
6. Extract the artifact and install `app-debug.apk` on an Android phone.

The workflow builds the debug APK on a GitHub-hosted Ubuntu runner using JDK 17 and Gradle 8.11.1.

## Local Android Studio build

Open the project root in Android Studio and run the `app` configuration, or use Gradle:

```bash
gradle assembleDebug
```

APK output:

`app/build/outputs/apk/debug/app-debug.apk`
