# Pls Revise 📚

**Pls Revise** is a high-fidelity, offline-first automated spaced-repetition and study management application built for Android. Designed with a hyper-professional, ultra-clean aesthetic inspired by premium modern productivity tools, it helps students and self-learners orchestrate their curriculum, track consistency, and systematically retain knowledge over long horizons.

---

## ✨ Features

- **Dynamic Spaced-Repetition Hierarchy:** Schedule revisions flexibly at any tier—by Chapter, Topic, or Subtopic.
- **Smart Task Management:** The "Objectives Due Today" engine visualizes your daily workflow with persisting strikethrough states, ensuring you see exactly what you accomplished each day.
- **Advanced Interval Scheduling:** Supports pre-loaded strategic intervals (1, 3, 7, 14, 30 days) alongside a Material 3 absolute multi-date calendar selection mechanism.
- **Gamified Analytics Suite:** Features a dynamic Level & XP progression loop, day-over-day workload velocity charts, and an unbroken habit-streak engine.
- **Local-First & Private:** Running 100% offline with zero remote servers or external trackers. Your data, notes, and attached documents stay strictly isolated on your device storage.

---

## 🛠️ Architecture & Tech Stack

This application is engineered using modern Android development best practices and clean architecture principles:

- **UI Framework:** 100% Declarative **Jetpack Compose** with optimized state hoisting.
- **Navigation:** Integrated `HorizontalPager` allowing smooth, fluid swipe transitions across foundational app domains.
- **Local Storage Engine:** **Room Database** managing structured relational tables with robust cascading deletes.
- **Concurrency & State Processing:** Kotlin Coroutines & Asynchronous `StateFlow` structures running operations off the Main Thread for 60 FPS scrolling stability.
- **Dependency Management:** Modern `libs.versions.toml` version cataloging.

---

## 📂 Project Blueprint

- `manifests/` — Coordinates global operating system hooks, launcher assets, and hardware rules.
- `kotlin+java/` — Clean MVVM logic separation (Entities, DAOs, ViewModels, and Composable screen views).
- `res/` — Decoupled system resources housing structural drawables, multi-density launch icons, and localized themes.

3. Sync the Gradle files to automatically download all required dependencies.
4. Select an Android Emulator or attach a physical device and hit **Run**.
