# Shopping List App

A reactive, single-page Flutter application that allows users to manage a daily shopping list dynamically. Built as an introductory hands-on project with **Flutter** and **Dart**.

---

## Features

* **Dynamic Item List:** Rendered using `ListView.builder` for efficient scrolling and performance.
* **Interactive Addition:** Easily add custom items using an interactive `TextField` and **Add** button (or by hitting **Enter**).
* **Mark as Bought:** Click any item or its checkbox to strike through completed items with a dynamic remaining items count in the header.
* **Validation & Snackbars:**
  * Prevents blank submissions with instant warning feedback.
  * Prevents duplicate entries on the list.
* **Item Deletion & Swipe-to-Dismiss:**
  * Delete items using the individual trash icon buttons.
  * Swipe items horizontally to delete via `Dismissible`.
* **Undo Functionality:** Restores accidentally deleted items with a single tap on the SnackBar **Undo** action.

---

## Screenshots

| Initial View                                             | Item Checked / Bought                                | Deleting & Undo                                    |
| :------------------------------------------------------: | :--------------------------------------------------: | :------------------------------------------------: |
| ![Initial View](Screenshot-Create%20and%20run%20App.png) | ![Marked as Bought](Screenshot-Type%20an%20item.png) | ![Deleting Items](Screenshot-List%20few%20tems.png)|
---

## Built With

* **[Flutter](https://flutter.dev/)** - Multi-platform UI toolkit.
* **[Dart](https://dart.dev/)** - Client-optimized programming language.
* **Material Design 3** - Modern, clean design system with custom color schemes.

---

## Project Structure
lib/
└── main.dart       # Main application entry point containing custom widgets & app state
pubspec.yaml         # Dependencies and project configurations


---

## 💻 How to Run Locally

### Prerequisites
* [Flutter SDK](https://docs.flutter.dev/get-started/install) installed and configured.
* Google Chrome (or any preferred web browser/emulator).

### Steps
1. **Clone or download this repository**:
   ```bash
   git clone <your-repository-url>

    Navigate into the project directory:
    Bash

    cd shopping_list1

    Get dependencies:
    Bash

    flutter pub get

    Run the app:
    Bash

    flutter run -d chrome

### Author

    Niyokuri Berenice
