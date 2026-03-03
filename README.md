# 📉 Expense Tracker App (Flutter)

A collaborative demo project built with **Flutter Clean Architecture**. This project serves as a technical foundation for our team to build a scalable expense tracking solution.

## 🚀 Getting Started
Ensure you have the agreed-upon versions installed:
* **Flutter SDK:** 3.41.x (Stable)
* **JDK:** 17
* **State Management:** (TBD - e.g., Bloc/Cubit)

## 🏗️ Project Architecture (Feature-First)
We are using a **Clean Architecture** approach to keep our code modular and testable.

### `lib/core`
Shared logic, app-wide constants (`AppColors`), themes, and reusable global widgets.

### `lib/features`
Contains independent features based on our Figma design:
* **Auth**: Registration and Login flows.
* **Tracker**: Main dashboard, expense logs, and spending trends/graphs.
* **Debts**: Management for borrowed and lent funds.
* **Settings**: User profile and app preferences.

---

## 🛠️ Folder Breakdown (Internal)
Each feature is divided into three layers:
1. **Data**: Repository implementations and Data Sources (API/Local DB).
2. **Domain**: Pure business logic (Entities and Use Cases).
3. **Presentation**: UI Logic (Blocs/Providers), Pages, and feature-specific Widgets.

## 🎨 Design Reference
Refer to the [Figma Design](https://www.figma.com/design/g3GPAH057ijWhHUTE5uiOh/Expense-Tracker-UI?node-id=0-1&t=ShXdE7g85yNzrWkH-1) for styling, spacing, and assets.
