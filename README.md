_## 📱 Multi-Form Flutter App

This is a simple Flutter application that allows users to input their personal details and view them on a confirmation screen. The app demonstrates form validation, navigation between screens, and the use of TextEditingController for input fields.

## 🚀 Features

Form Input: Name, Email, Phone Number, Address

Form Validation: Email and phone number validation

Navigation: Moves to a confirmation screen after form submission

Clean UI: Simple and intuitive interface

## 🛠️ Installation

Clone the repository:

Install dependencies:

flutter pub get

Run the app:

flutter run

## 🧱 Project Structure

.
├── lib
│   ├── main.dart               # App entry point
│   ├── screens
│       ├── home_screen.dart    # Form input screen
│       └── confirmation_screen.dart  # Confirmation screen
└── pubspec.yaml

## 🧩 Code Overview

## main.dart

Initializes the app with MyApp.

Sets HomeScreen as the default home widget.

## home_screen.dart

Displays a form with fields for name, email, phone, and address.

Validates name, email, and phone number inputs.

On successful validation, navigates to the ConfirmationScreen.

## confirmation_screen.dart

Displays the submitted user information.

Provides a Go Back button to return to the HomeScreen.

## ⚙️ Validation Rules

Name: Required

Email: Must be in valid email format

Phone: Must be exactly 10 digits


## 🤝 Contributing

Fork the repo.

Create a new branch: git checkout -b feature/awesome-feature

Commit your changes: git commit -m 'Add some awesome feature'

Push to the branch: git push origin feature/awesome-feature

Submit a pull request 🚀

📜 License

This project is licensed under the MIT License.

