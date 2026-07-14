# 📋 Task Management App

A modern and responsive Flutter Task Management application built using the **Provider** state management package. This application allows users to efficiently manage their daily tasks with features such as adding, editing, deleting, searching, filtering, and tracking task completion. The project demonstrates clean architecture, state management, and Flutter best practices.

---

## 🚀 Features

### ✅ Task Management

* Add new tasks
* Edit existing tasks
* Delete tasks
* Mark tasks as completed or pending
* Undo deleted tasks

### 🔍 Search & Filter

* Search tasks by title
* Filter tasks by:

  * All Tasks
  * Completed
  * Pending
  * High Priority

### 📅 Task Details

Each task contains:

* Title
* Description
* Due Date
* Priority Level
* Category
* Completion Status

### 📊 Dashboard

* Total Tasks
* Completed Tasks
* Pending Tasks
* Progress Indicator

### 🎨 User Interface

* Material 3 Design
* Responsive Layout
* Light & Dark Theme
* Smooth Animations
* Floating Action Button (FAB)
* Modern Cards and UI Components

### ⚡ State Management

* Provider Package
* Real-time UI Updates
* Efficient Widget Rebuilding using `Consumer`

### 💾 Local Storage

* Store tasks using SharedPreferences
* Automatically load saved tasks when the app starts

---

## 🛠️ Technologies Used

* Flutter
* Dart
* Provider
* SharedPreferences
* Material 3

---

## 📂 Project Structure

```text
lib/
│
├── models/
│   └── task.dart
│
├── providers/
│   └── task_provider.dart
│
├── screens/
│   ├── home_screen.dart
│   ├── add_task_screen.dart
│   ├── edit_task_screen.dart
│
├── widgets/
│   ├── task_card.dart
│   ├── custom_button.dart
│   ├── search_bar.dart
│
├── services/
│   └── storage_service.dart
│
├── utils/
│   ├── constants.dart
│   └── themes.dart
│
└── main.dart
```

---

## 📦 Packages Used

```yaml
dependencies:
  flutter:
    sdk: flutter

  provider: ^6.1.2
  shared_preferences: ^2.2.3
  intl: ^0.19.0
```

---

## 📱 Screens

* Home Screen
* Add Task Screen
* Edit Task Screen
* Task Details
* Search & Filter View

---

## ▶️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/task-management-app.git
```

### 2. Navigate to the Project

```bash
cd task-management-app
```

### 3. Install Dependencies

```bash
flutter pub get
```

### 4. Run the App

```bash
flutter run
```

---

## 🧠 Learning Objectives

This project demonstrates:

* Provider State Management
* Flutter Widget Tree
* ChangeNotifier & Consumer
* State Sharing Across Screens
* Local Data Persistence
* CRUD Operations
* Search & Filter Functionality
* Responsive UI Design
* Material 3 Components
* Flutter Project Architecture
* Clean Code Practices

---
 👨‍💻 Author

**Talha**

Software Engineering Student | Flutter Developer
---

## 📄 License

This project is developed for educational purposes and is open for learning and personal use.
