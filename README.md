# Patient Management App — Android

A university project: an Android application for patient management, featuring secure authentication and local data storage with SQLite.

## Features

- Patient registration with username, email, and password
- Secure login with credential validation
- Local data persistence using SQLite
- Input validation (empty fields, email format, password confirmation)

## Tech Stack

| Layer | Technology |
|---|---|
| Language | Kotlin |
| Platform | Android (AndroidX) |
| Database | SQLite (via `SQLiteOpenHelper`) |
| IDE | Android Studio |

## Project Structure

```
app/src/main/java/com/example/myapplicationtest/
├── MainActivity.kt      # Entry point
├── LOGIN.kt             # Login screen
├── REGISTER.kt          # Patient registration screen
└── DBHelper.kt          # SQLite database helper
```

## Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/Nour-Chtourou/android-login-app.git
   ```
2. Open the project in **Android Studio**
3. Run on an emulator or physical device (API 21+)

## Author

**Nour Chtourou** — [LinkedIn](https://www.linkedin.com/in/nour-chtourou19)
