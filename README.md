
# Todo App

A clean, cross-platform task manager built with Flutter. Create, edit, and organize your daily tasks with due dates, priorities, and a calendar view.

<p align="center">
  <img src="https://github.com/user-attachments/assets/6926f121-e5e4-479b-a13a-1479fce1913f" width="250" alt="Home Screen" />
  <img src="https://github.com/user-attachments/assets/d9a47cd6-4eb1-489c-95f9-5ce07f177bb5" width="250" alt="Create Task" />
  <img src="https://github.com/user-attachments/assets/eaf4e504-21c9-41bf-b0a6-e9b613218e62" width="250" alt="Task Details" />
</p>

## Features

- **Create tasks** — add a task with a title, description, start/end date, and priority.
- **Edit tasks** — update the details of an existing task.
- **Calendar view** — browse tasks by date with a custom calendar card.
- **Priorities** — tag each task with a priority level.
- **Date formatting** — readable dates powered by `intl`.
- **Polished UI** — animated splash screen, custom buttons, text fields, and info cards.

## Tech Stack

- **Flutter** (Dart SDK `^3.9.2`)
- **flutter_svg** — SVG icon rendering
- **intl** — date formatting
- **cupertino_icons**

## Project Structure

```
lib/
├── main.dart
├── model/
│   └── task_model.dart                  # Task data model (title, dates, priority)
├── screen/
│   ├── splash_screen.dart
│   ├── home_screen.dart                 # Task list + calendar
│   ├── create_a_new_task_screen.dart    # Add a task
│   └── widgets/                         # edit_task, calendar_card, buttons, fields, info_card
└── util/
    ├── colorconstraint.dart             # Color constants
    └── routes/                          # App routes & page definitions
```

## Getting Started

### Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (Dart `^3.9.2`)

### Setup

1. Install dependencies:
   ```bash
   flutter pub get
   ```

2. Run the app:
   ```bash
   flutter run
   ```

### Build

```bash
flutter build apk        # Android
flutter build ios        # iOS

```

## Supported Platforms

Android · iOS 

