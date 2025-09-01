# Expense Tracker App

A simple **Flutter** application to track your daily expenses and visualize them using a bar chart.

---

## Features

* **Add Expenses**
  Users can add expenses with the following details:

  * **Title** – Name or description of the expense
  * **Date** – When the expense occurred
  * **Amount** – Cost of the expense
  * **Category** – Select from predefined categories

* **View Expenses**

  * Display all expenses in a **bar chart** for a quick visual summary
  * Easy-to-read and interactive UI

---

## Screenshots

*Add some screenshots here to show your app’s UI.*

---

## Getting Started

### Prerequisites

* Flutter SDK installed
* Android Studio, VS Code, or any preferred IDE
* Device emulator or physical device for testing

### Installation

1. Clone the repository:

   ```bash
   git clone <your-repo-url>
   ```
2. Navigate to the project folder:

   ```bash
   cd expense_tracker
   ```
3. Install dependencies:

   ```bash
   flutter pub get
   ```
4. Run the app:

   ```bash
   flutter run
   ```

---

## Project Structure

* **lib/** – Contains all the Dart files

  * `main.dart` – Entry point of the app
  * `models/` – Data models (e.g., Expense model)
  * `screens/` – App screens (e.g., HomeScreen, AddExpenseScreen)
  * `widgets/` – Reusable UI components (e.g., BarChart, ExpenseList)

---

## Dependencies

* `flutter` – SDK
* `charts_flutter` or any chart library – For displaying bar charts
* `provider` (optional) – For state management

---

## Usage

1. Open the app.
2. Click **Add Expense** button.
3. Fill in **Title**, **Amount**, **Date**, and **Category**.
4. Save the expense.
5. View all expenses in the home bar chart.

---

## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Create a Pull Request

---

## License

This project is licensed under the MIT License.
