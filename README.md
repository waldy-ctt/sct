# Simple Calorie Tracker

<img src="https://github.com/user-attachments/assets/31b11fdb-5bb3-4e45-9eb4-36a74bd438de" alt="app screenshot" height="400">
<img src="https://github.com/user-attachments/assets/e50f6aea-4b3b-44b5-aab4-a8ef274b509a" alt="app screenshot" height="400">

## Features

- Search foods by name or barcode with [OpenFoodFacts](https://openfoodfacts.org/) and [USDA](https://fdc.nal.usda.gov/) api integration
- Track calories, protein, fat, and carbohydrates in a daily diary
- Add custom entries with your own nutritional values
- Save your favorite foods for quick access
- Customize your daily targets

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/antomanc/simple-calorie-tracker.git
    cd simple-calorie-tracker
    ```
2. Install dependencies with bun
    ```bash
    bun install
    ```
3. Prebuild for native platforms (Android/iOS):
    ```bash
    bun run expo prebuild
    ```
4. Build the APK:
    ```bash
    cd android
    ./gradlew assembleRelease
    ```
    The release APK will be located in `android/app/build/outputs/apk/release/` as `app-release.apk`.

Feel free to open issues or suggest features!
