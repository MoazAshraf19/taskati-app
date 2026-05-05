# Taskati - Task Management & Daily Organization App

<img width="1672" height="941" alt="taskati_github_banner" src="https://github.com/user-attachments/assets/985be331-0434-483b-9316-9f6ac79c50cd" />


## Project Overview

Taskati is a Flutter mobile application designed to help users organize daily tasks, track progress, and manage task status in a simple and clean interface.

The app includes task creation, editing, completion tracking, date and time selection, local data storage, and light/dark theme support. It is built as a practical portfolio project focused on Flutter UI, local persistence, reusable widgets, and organized project structure.

## Project Type

Flutter mobile task management application.

## Project Summary

| Item | Description |
|---|---|
| Project Name | Taskati |
| Platform | Android |
| Framework | Flutter |
| Language | Dart |
| Database | Hive local database |
| Project Type | Task Management App |
| Status | UI and local task flow completed |
| Theme Support | Light and Dark Mode |

## 🎯 Key Features Overview

![Flutter Productivity App](https://img.shields.io/badge/Flutter-Productivity%20App-blue?style=for-the-badge&logo=flutter)
![Dart](https://img.shields.io/badge/Dart-Language-0175C2?style=for-the-badge&logo=dart)
![Hive](https://img.shields.io/badge/Hive-Local%20Storage-FFA500?style=for-the-badge)
![Light & Dark Mode](https://img.shields.io/badge/Theme-Light%20%26%20Dark-FFD700?style=for-the-badge)

### Core Features

- **Task Management** - Create, edit, complete, and delete tasks efficiently
- **Local Storage** - All data stored locally using Hive for offline access
- **Theme Support** - Seamless Light and Dark mode experience
- **Date & Time Scheduling** - Intuitive date picker and time selection
- **Task Filtering** - Filter tasks by All, In Progress, or Completed status
- **Profile Setup** - Complete user profile with image and name
- **Daily Progress Tracking** - Visual progress indicator for daily tasks

## Main Features

### Splash Screen

Displays the Taskati brand identity and introduces the app before moving to the next user flow.

### Complete Profile Flow

Allows the user to add a profile image and name before starting to use the app.

### Home Dashboard

Shows the user greeting, selected date, daily progress, date selector, task filters, and task list.

### Task Management

Users can create, edit, complete, and delete tasks. Each task includes a title, description, date, start time, end time, and status.

### Task Filtering

Tasks can be filtered by:

- All
- In Progress
- Completed

### Date and Time Scheduling

The app allows users to select task dates, start times, and end times using organized input cards.

### Local Data Persistence

Task data and user preferences are stored locally using Hive, so the app can keep data between sessions.

### Light and Dark Theme

The app supports both light and dark mode, giving users a comfortable experience in different environments.

## Screens Included

1. Splash Screen
2. Complete Profile Screen
3. Home Screen - Light Mode
4. Home Screen - Dark Mode
5. Add Task Screen - Light Mode
6. Add Task Screen - Dark Mode
7. Task List with Swipe Actions
8. Profile Setup UI

## Tech Stack and Packages

| Technology / Package | Usage |
|---|---|
| Flutter | Building the mobile app UI |
| Dart | Application logic and structure |
| Hive | Local NoSQL database for task storage |
| hive_flutter / hive_ce_flutter | Flutter integration for Hive |
| intl | Date and time formatting |
| date_picker_timeline | Horizontal date picker UI |
| flutter_slidable | Swipe actions for task cards |
| percent_indicator | Daily progress indicator |
| image_picker | Selecting profile image from camera or gallery |
| flutter_svg | Rendering SVG assets |
| lottie | Splash/onboarding animation support |
| shared_preferences | Saving simple user preferences |
| gap | Clean spacing between widgets |

## Project Architecture

The project is organized using a feature-based structure with shared core utilities and reusable components.

```text
lib/
├── main.dart
├── core/
│   ├── constants/
│   ├── functions/
│   ├── models/
│   ├── services/
│   ├── styles/
│   └── widgets/
│
├── features/
│   ├── splash/
│   ├── complete_profile/
│   ├── home/
│   └── add_task/
│
└── hive/
```

## Folder Responsibilities

### core

Contains shared app logic, constants, styles, models, helper functions, services, and reusable widgets used across the application.

### features

Contains the main app modules such as splash, complete profile, home, and add task screens.

### hive

Contains Hive adapters and generated files used for local database serialization.

## Reusable Components

The project includes reusable UI components such as:

- Main button
- Custom text field
- Tab button
- SVG picture widget
- Dialog components
- Date/time card
- Task card
- Daily progress widget

These components help keep the app consistent and reduce repeated UI code.

## UI/UX Design Notes

Taskati uses a clean productivity-focused visual style with:

- Purple primary color for main actions
- Light and dark themes
- Rounded cards and soft shadows
- Clear task hierarchy
- Large readable typography
- Simple filter tabs
- Floating action button for quick task creation
- Swipe actions for task completion and editing

## What I Learned

While building this project, I practiced:

- Creating Flutter screens from a UI design
- Building reusable widgets
- Managing local data with Hive
- Handling task creation and editing flows
- Working with date and time formatting
- Using light and dark themes
- Organizing code using feature-based folders
- Preparing a Flutter project for GitHub and portfolio presentation

## How to Run the Project

```bash
git clone REPOSITORY_LINK_HERE
cd taskati
flutter pub get
flutter run
```

Replace `REPOSITORY_LINK_HERE` with the actual GitHub repository link.

## Screenshots

| Splash | Home Light | Home Dark |
|---|---|---|
| ![Splash](screenshots/01_splash.png) | ![Home Light](screenshots/02_home_light.png) | ![Home Dark](screenshots/03_home_dark.png) |

| Add Task Light | Add Task Dark | Complete Profile |
|---|---|---|
| ![Add Task Light](screenshots/04_add_task_light.png) | ![Add Task Dark](screenshots/05_add_task_dark.png) | ![Complete Profile](screenshots/06_complete_profile.png) |

## Future Enhancements

- Add task categories
- Add notifications and reminders
- Add task priority levels
- Add calendar view
- Add search functionality
- Add cloud sync
- Add unit and widget tests
- Improve onboarding experience

## Project Status

The core UI and local task management flow are completed. Future updates may include reminders, cloud sync, task categories, and testing.

## Author

Moaz Ashraf Fayez  
Junior Flutter Developer

## License

This project is created for learning and portfolio purposes.
