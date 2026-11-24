# Kaas Expense Tracker

A vibe-coded Android expense tracker. Built for fun and for keeping tabs on where the money goes.

> Don't blame me if the IT guy comes knocking. 👀

## Overview

Kaas Expense Tracker is a native Android app written in Kotlin. It helps you log your spending and keep an eye on your expenses without any fuss.

<!-- TODO: Add a screenshot or GIF of the app here -->
<!-- ![Screenshot](docs/screenshot.png) -->

## Features

<!-- TODO: Edit this list to match what the app actually does -->
- Add and record expenses
- View a list of past expenses
- Categorize spending
- Track totals at a glance

## Tech Stack

- **Language:** Kotlin 1.9.24
- **Platform:** Android
- **Build system:** Gradle (Kotlin DSL) with Android Gradle Plugin 8.5.0
- **IDE:** Android Studio

## Getting Started

### Prerequisites

- [Android Studio](https://developer.android.com/studio) (a recent version that supports AGP 8.5.0 or newer)
- JDK 17
- An Android device or emulator

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ArjunSindhya/kaas-expense-tracker.git
   cd kaas-expense-tracker
   ```

2. Open the project in Android Studio and let Gradle sync.

3. Run the app on an emulator or a connected device from Android Studio (**Run ▶ Run 'app'**).

### Build from the command line

```bash
# Debug APK
./gradlew assembleDebug

# Install on a connected device
./gradlew installDebug
```

On Windows, use `gradlew.bat` instead of `./gradlew`.

The debug APK will be generated at `app/build/outputs/apk/debug/`.

## Project Structure

```
kaas-expense-tracker/
├── app/                    # Android application module
├── gradle/wrapper/         # Gradle wrapper files
├── build.gradle.kts        # Root build configuration
├── settings.gradle.kts     # Project settings
├── gradle.properties       # Gradle properties
├── gradlew / gradlew.bat   # Gradle wrapper scripts
└── README.md
```

## Roadmap

- [ ] Charts and spending insights
- [ ] Export data (CSV)
- [ ] Budgets and alerts
- [ ] Dark mode polish

## Contributing

This is a personal project, but suggestions are welcome. Feel free to open an issue or submit a pull request.

1. Fork the repo
2. Create a feature branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -m "Add my feature"`)
4. Push to the branch (`git push origin feature/my-feature`)
5. Open a pull request

## Disclaimer

This project was vibe coded, so expect rough edges. Use it at your own risk, and don't put anything sensitive in it without reviewing the code first.

## License

No license has been specified yet. Add a `LICENSE` file (for example, MIT) to let others know how they can use this code.

## Author

Made by [@ArjunSindhya](https://github.com/ArjunSindhya)
