Here’s an improved version of your README file, with clearer structure, formatting, and enhanced clarity:

---

# 📘 Attendance Tracker App

## 📝 Overview

**Attendance Tracker App** is an Android application designed to help teachers easily **record**, **view**, and **track** student attendance. It leverages **Firebase Firestore** as its backend, offering secure and real-time data storage and retrieval.

---

## 🚀 Features

* ✅ **Record Attendance** — Mark attendance using a student list with checkboxes.
* 📊 **View Overall Attendance** — Display class-wide attendance statistics.
* 👤 **View Individual Attendance** — Access detailed logs for each student.

---

## 🔧 Prerequisites

Before setting up the project, ensure you have:

* ✅ Android Studio installed.
* ✅ A Firebase project with Firestore enabled.
* ✅ An Android device or emulator for testing.

---

## 📥 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/firasbarkia/attendance-tracker.git
```

### 2. Open in Android Studio

* Launch **Android Studio**.
* Click **Open an existing project**.
* Select the cloned `attendance-tracker` folder.

### 3. Set Up Firebase

1. Go to [Firebase Console](https://console.firebase.google.com).
2. Create a new project or select an existing one.
3. Add an **Android app** to your Firebase project.
4. Download the `google-services.json` file.
5. Place it inside the `app/` directory.

### 4. Sync with Gradle

In Android Studio:

```
File > Sync Project with Gradle Files
```

---

## ▶️ Usage

### 🔹 `MainActivity`

Navigation screen with buttons to access each feature.

### 🔹 `RecordAttendanceActivity`

* Displays a list of students.
* Teachers can mark each student as **Present** or **Absent**.

### 🔹 `ViewAttendanceActivity`

* Shows overall attendance data fetched from Firestore.

### 🔹 `ViewStudentAttendanceActivity`

* Allows viewing attendance records per student.

---

## 🔗 Firebase Integration

This app uses **Firebase Firestore** to store and retrieve attendance data. Ensure that:

* Firestore rules are correctly configured.
* `google-services.json` is correctly placed.
* Firebase dependencies are added in the `build.gradle` files.

---

## 🧩 Code Structure

### 📦 Model

* `AttendanceRecord.java` — Represents each student’s attendance data.

### 🧰 Adapters

* `AttendanceRecordAdapter.java` — Adapter for class attendance list.
* `StudentAttendanceRecordAdapter.java` — Adapter for individual student records.

### 🎨 Layouts

* `activity_main.xml` — Main screen with navigation.
* `activity_record_attendance.xml` — UI for marking attendance.
* `activity_view_attendance.xml` — Displays class-level attendance.
* `activity_view_student_attendance.xml` — Shows individual records.
* `item_attendance_record.xml` — List item layout for attendance.
* `item_student_attendance_record.xml` — List item layout for student records.

---

## 🤝 Contributing

We welcome contributions! To get started:

1. **Fork** the repo.
2. Create your feature branch:
   `git checkout -b feature/YourFeature`
3. Commit your changes:
   `git commit -m "Add new feature"`
4. Push to GitHub:
   `git push origin feature/YourFeature`
5. Open a **Pull Request**.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

* Built using [Firebase Firestore](https://firebase.google.com/docs/firestore) for backend storage.
* Inspired by the amazing Android open-source community.

---
