# SwiftTracker

**SwiftTracker is a privacy-first iOS app for tracking spending and betting activity, turning everyday transactions into actionable insights and healthier financial habits.**

Rather than functioning as a simple transaction log, SwiftTracker helps users understand behavioral patterns through trend analysis, configurable alerts, and personalized thresholds—all while keeping data under the user's control.

## ✨ Features

### 📊 Behavioral & Trend Analysis

Visualize spending and betting activity over time with interactive charts and summaries.

* Daily, weekly, and monthly insights
* Category-based analysis
* Historical activity tracking
* Identify recurring patterns and changes in behavior
* Interactive SwiftUI charts

### ⚡ Fast Activity Logging

Record an expense or bet in seconds.

Each entry can include:

* Amount
* Category
* Date
* Activity type
* Notes

Entries are organized into a searchable history for quick review.

### 🔔 Smart Alerts & Reminders

Set personalized thresholds and receive notifications when activity approaches predefined limits.

Examples include:

* Spending limits
* Daily activity thresholds
* Personal targets
* Custom reminders

These alerts are designed to help users recognize patterns early rather than only reviewing them after the fact.

### 🔐 Privacy-First Architecture

SwiftTracker is designed with privacy as a core principle.

* Data can remain stored locally on the device
* No cloud account is required for core functionality
* Optional encryption can protect stored data
* iCloud synchronization is opt-in

Your data stays under your control.

### ☁️ Optional iCloud Sync

Enable iCloud to synchronize your SwiftTracker data across supported Apple devices.

This provides:

* Cross-device synchronization
* Automatic backups
* Seamless access across Apple devices

iCloud functionality is optional.

### 🎨 Native SwiftUI Experience

Built with **SwiftUI**, SwiftTracker provides a modern Apple-native interface designed for iPhone and iPad.

* Light Mode and Dark Mode support
* Responsive layouts
* Native navigation
* iPhone and iPad support
* Accessibility-conscious UI design

---

## 🛠️ Technology Stack

SwiftTracker is built using Apple's native development technologies.

| Technology             | Purpose                               |
| ---------------------- | ------------------------------------- |
| **Swift**              | Application development               |
| **SwiftUI**            | User interface                        |
| **iOS**                | Mobile platform                       |
| **iCloud**             | Optional cross-device synchronization |
| **User Notifications** | Alerts and reminders                  |
| **Swift Charts**       | Data visualization                    |
| **Xcode**              | Development environment               |

---

## 🚀 Getting Started

### Requirements

* **Xcode 15 or later**
* **iOS 17 or later**
* macOS compatible with your installed Xcode version
* iPhone/iPad or iOS Simulator

### Clone the Repository

```bash
git clone https://github.com/bigjermaine/SwiftTracker.git
cd SwiftTracker
```

### Open the Project

```bash
open SwiftTracker.xcodeproj
```

Alternatively, open `SwiftTracker.xcodeproj` directly in Xcode.

### Build & Run

1. Select an iOS Simulator or connected device.
2. Open the `SwiftTracker` scheme.
3. Press **⌘R** to build and run.
4. Create your first expense or betting entry.

---

## 🏗️ Project Goals

SwiftTracker is built around a simple idea:

> **Tracking behavior should help you understand it—not simply record it.**

The project explores how native iOS technologies can be used to transform raw activity data into meaningful, privacy-conscious insights.

---

## 🔒 Privacy

Privacy is a fundamental part of SwiftTracker's design.

The application is designed to minimize reliance on external services and keep user data local whenever possible. Optional synchronization features allow users to choose whether they want their data available across Apple devices.

For production deployments, review the application's privacy configuration, encryption implementation, and iCloud entitlements before enabling these capabilities.

---

## 🤝 Contributing

Contributions, improvements, and suggestions are welcome.

To contribute:

1. Fork the repository.
2. Create a feature branch.

```bash
git checkout -b feature/your-feature
```

3. Make your changes.
4. Commit your work.

```bash
git add .
git commit -m "Add your change"
```

5. Push the branch.

```bash
git push origin feature/your-feature
```

6. Open a Pull Request.

---

## 📄 License

Add your preferred open-source license here, such as **MIT**, if you intend to distribute SwiftTracker under an open-source license.

---

### GitHub Tagline

**Privacy-first iOS spending and betting tracker with behavioral insights, smart alerts, and optional iCloud sync.**

