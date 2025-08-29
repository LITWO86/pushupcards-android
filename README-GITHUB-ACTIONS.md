# Push-UP Cards Android Project + GitHub Actions

This repository contains the Android WebView wrapper for Push-UP Cards and a GitHub Actions workflow to build a Google Play-ready .aab in the cloud.

## How to use
1. Upload this project to a GitHub repository (root level contains `settings.gradle`, `app/`, `.github/workflows/build.yml`).
2. Go to the Actions tab on GitHub and run **Android Build (Cloud AAB)**.
3. After the job completes, download the artifact **pushupcards-aab** — inside is your `.aab` file ready for Play Console.

Notes:
- Update `versionCode` in `app/build.gradle` for each new release.
- The workflow installs Gradle 8.7 automatically and builds with JDK 17.
