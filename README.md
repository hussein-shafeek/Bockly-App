# 📚 Bookly App (MVVM)

Bookly is a sophisticated book browsing application built with **Flutter**, designed to provide users with a seamless and visually appealing experience when discovering free books.

This project demonstrates modern Flutter development practices with a strong focus on the **MVVM architecture**, clean state management, and premium UI design.

<p align="center">
  <img src="assets/images/bookly_logo.jpg" alt="Bookly Logo" width="150"/>
</p>

---

## 🎥 App Demo Video
Watch the full application flow and UI demo here:  
https://drive.google.com/drive/folders/13ikic0Rj8HOgjf3r_LBUx61vy3Vv-U86

---

## 🚀 Project Overview

The application fetches book data from the **Google Books API**, allowing users to:

- Browse **Featured** and **Newest** books
- Search for specific books with optimized queries
- View detailed book information
- Explore **Similar Book** recommendations
- Enjoy a smooth and responsive UI with proper error handling and loading states

---

## ✨ Key Features

- **MVVM Architecture**  
  Clear separation between UI, business logic, and data handling for better maintainability and scalability.

- **Bloc & Cubit State Management**  
  Efficient and predictable state management using `flutter_bloc`.

- **Responsive UI**  
  Adaptive layouts that provide a consistent experience across different screen sizes and devices.

- **Interactive Search**  
  Optimized search with input validation and debouncing to reduce unnecessary API calls.

- **Dark Mode**  
  Sleek and modern dark theme built using a custom color palette.

- **Robust Error Handling**  
  Functional error handling using the `Either` type to gracefully manage network failures and unexpected exceptions.

---

## 🛠️ Tech Stack & Libraries

- **Framework:** Flutter & Dart  
- **Architecture:** MVVM  
- **State Management:** flutter_bloc (Cubit)  
- **Networking:** Dio with Interceptors  
- **Dependency Injection:** GetIt  
- **Routing:** GoRouter  
- **Functional Programming:** Dartz  
- **Value Equality:** Equatable  
- **Image Caching:** cached_network_image  
- **Fonts:** Google Fonts  
- **Launcher Icons:** flutter_launcher_icons  

---

## 📂 Project Structure

```text
lib/
├── core/                   # Shared utilities, services, and constants
├── features/               # Feature-based MVVM structure
│   ├── home/               # Home feature (View + ViewModel)
│   ├── search/             # Search feature
│   └── splash/             # Splash screen
├── main.dart               # App entry point
└── ...
