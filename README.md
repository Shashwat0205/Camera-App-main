LINK FOR THE THE APK FILE -https://drive.google.com/file/d/1RWtjbZuyojV-UcnjNAnR6VB9miiDSn7J/view?usp=sharing

# Camera App

## Overview
This Camera app allows users to take photos and record videos using their device's camera. It utilizes the Android CameraX library for camera functionalities and follows the MVVM (Model-View-ViewModel) architecture.

## Main Features
- Capture photos
- Record videos
- Switch between front and back cameras
- View captured media in the gallery

## Technologies Used
- Android CameraX
- Jetpack Compose
- Dagger Hilt for Dependency Injection
- Kotlin Coroutines for asynchronous operations
- MVVM Architecture

## Installation and Setup

### Prerequisites
- Android Studio
- Android SDK
- Git

### Steps
1. Clone the repository:
    ```
    https://github.com/Shashwat0205/Camera-App-main.git
    ```
2. Open the project in Android Studio.
3. Sync the project with Gradle files.
4. Build and run the project on an emulator or physical device.

## Architecture

The project follows the MVVM (Model-View-ViewModel) architecture.

### Model
- **CameraRepository**: Interface defining methods for camera operations.
- **CameraRepositoryImpl**: Implementation of `CameraRepository` that interacts with the CameraX API.

### View
- **CameraScreen**: Composable function that defines the UI.
- **SplashActivity**: Displays the splash screen.
- **MainActivity**: Main entry point of the app.

### ViewModel
- **CameraViewModel**: Manages the UI-related data and handles the business logic by interacting with the `CameraRepository`.

### Dependency Injection
- **CameraRepositoryModule**: Dagger Hilt module that provides dependencies for `CameraRepository`.

