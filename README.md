# DevConnect 🚀

**DevConnect** is a community-driven collaboration and productivity platform built specifically for student developers, tech enthusiasts, and independent creators—tailored for tech hubs like Pune and Kolhapur. It combines real-time project feeds, team matching, skill filtering, and gamified productivity tracking (streaks and XP points) into a single ecosystem.

---

## 🌟 Key Features

* **Real-Time Project Feed**: Discover and post open-source or team-building projects instantly synced via Firebase Firestore.
* **Smart Team Matching**: Search teams by tech stack, role (e.g., Android, React, Backend), or keywords.
* **Gamified Productivity & Streaks**: Track daily coding streaks, weekly collaboration hours, and XP progression with live interactive charts (MPAndroidChart).
* **Developer Profiles**: Customize your developer bio, tech stack badges, GitHub/LinkedIn links, and upload custom profile pictures with Firebase Storage & Glide integration.
* **Cross-Platform Presence**: Includes both a native Android application (Kotlin/Jetpack) and a high-end web landing page.

---

## 🛠️ Tech Stack

### Mobile App (Android)
* **Language**: Kotlin
* **Architecture**: MVVM with Repository Pattern, Kotlin Coroutines, and Flows
* **Backend & Database**: Firebase Authentication & Cloud Firestore (Real-time sync)
* **Storage**: Firebase Storage & Glide (Image loading & circular cropping)
* **UI Components**: Material Design 3, RecyclerView, ConstraintLayout, and MPAndroidChart

### Web Landing Page
* **Frontend**: HTML5, Modern CSS3, and Tailwind CSS
* **Design System**: Glassmorphism, dark-mode first UI, vibrant glowing accents, and fully responsive layouts

---

## 📂 Project Structure

```text
devconnect/
├── android/                  # Native Android application source code (Kotlin)
│   ├── app/src/main/java/com/example/devconnect/
│   │   ├── adapter/          # RecyclerView adapters for projects & feeds
│   │   ├── model/            # Data models (ProjectModel, UserActivity, etc.)
│   │   ├── repository/       # Firestore data repositories
│   │   ├── viewmodel/        # MVVM ViewModels & UI state handlers
│   │   └── *.kt              # Fragments (Home, Profile, JoinTeam, etc.)
│   └── app/src/main/res/     # Layouts (XML), drawables, and themes
└── web/                      # Web landing page files (HTML/Tailwind)
    └── index.html            # High-end responsive web landing page
