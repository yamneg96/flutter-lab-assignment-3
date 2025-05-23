# flutter-lab-assignment-3
---

# Assignment 3
# Name: Yamlak Negash
# ID: UGR/2910/15
# Seciton: 2

---

# 🖼️ Flutter Photo Album App

A modern Flutter application that displays a list of photo albums using clean architecture principles and the BLoC pattern for state management.

## 🚀 Features

- 🖼️ Displays photo albums with thumbnails and details
- 🔄 BLoC pattern for predictable state management
- 🌐 REST API integration using JSONPlaceholder
- 📦 Clean Architecture structure
- 🎨 Material Design 3 support

## 📁 Project Structure
```
lib/
├── 📂 app/ # Application-level configurations
│ ├── router.dart # App routing configuration
│ └── theme.dart # App theme configuration
│
├── 📂 core/ # Core functionality
│ ├── 📂 network/ # Network-related code
│ │ ├── api_service.dart # Retrofit API service
│ │ └── dio_client.dart # Dio HTTP client setup
│ └── 📂 utils/ # Utility functions and constants
│
├── 📂 features/ # Feature modules
│ └── 📂 albums/ # Photo albums feature
│ ├── 📂 data/ # Data layer (models, repositories)
│ ├── 📂 domain/ # Business logic layer
│ └── 📂 presentation/ # UI layer
│ ├── 📂 bloc/ # BLoC implementation
│ ├── 📂 pages/ # Screen implementations
│ └── 📂 widgets/ # Reusable UI components
│
└── main.dart # Application entry point
```
markdown
Copy
Edit

## 🛠️ Getting Started

1. 📥 Clone the repository
2. 🚀 Run `flutter pub get` to install dependencies
3. 🧪 Run the app with `flutter run`

## 📦 Dependencies

- `flutter_bloc` – State management
- `dio` – HTTP client for REST APIs
- `go_router` – Declarative navigation
- `json_serializable` – JSON parsing
- `retrofit` – Type-safe REST client

## 🧪 Testing

Run widget and unit tests with:
```bash
flutter test
📝 License
This project is licensed under the MIT License – see the LICENSE file for details.

👥 Contributing
Fork the repository

Create your feature branch

Commit your changes

Push to the branch

Create a new Pull Request

📞 Support
If you encounter any issues or have questions, feel free to open an issue in the repository.