iExpense 💸📱

A dynamic personal finance tracking application built with SwiftUI to help users manage, categorize, and monitor their personal expenses with ease.

📱 About The Project

iExpense is a sleek iOS application designed to solve everyday expense tracking challenges. Whether you are managing personal budgets, tracking business trips, or splitting bills, iExpense allows users to add, filter, and delete expenses categorized by type (Personal or Business).

This project demonstrates advanced SwiftUI concepts, including state management (@State, @ObservedObject), data persistence (UserDefaults and Codable), sheet presentation, and custom styling based on expense amounts.

🛠️ Built With

SwiftUI — Declarative UI framework for building modern iOS user experiences.

Combine — Reactive programming framework for state management and data flow.

Foundation (UserDefaults / Codable) — For robust local data persistence.

Xcode / iOS SDK — Primary development toolchain.

Git & GitHub — Version control and collaboration.

✨ Features

Categorized Tracking: Separate expenses into Personal and Business categories.

Dynamic Currency Formatting: Automatically formats values according to the user's preferred currency style.

Conditional Styling: Visual cues that highlight large expenses (e.g., color-coding amounts based on value thresholds).

Data Persistence: Automatically saves and loads your expense lists locally using UserDefaults and Codable.

Swipe-to-Delete: Easily remove unwanted or outdated expense items with standard iOS table gestures.


📂 Project Structure

iExpense/
├── iExpenseApp.swift       # App entry point
├── ContentView.swift       # Main list view with filtering and deletion
├── AddView.swift           # Modal view for adding new expenses
└── ExpenseItem.swift       # Data model conforming to Codable & Identifiable

