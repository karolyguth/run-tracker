# Run Tracker App

## Introduction
The Run Tracker App is a modern, mobile application designed to help users track and analyze their running sessions. Built using the latest technologies in the Android ecosystem, this app offers a clean, intuitive interface and robust features that cater to both amateur joggers and professional runners.

## Project Status
**Note:** This project is currently in development. Features and documentation are subject to change.

## Features
- **Run Tracking:** Automatically track your running routes, distances, and times.
- **Analytics:** View detailed statistics about your runs to monitor progress and performance improvements.
- **User Authentication:** Secure user authentication to ensure data privacy and personalization.

## Technology Stack
- **Language:** Kotlin
- **UI:** Jetpack Compose
- **Architecture:** Clean Architecture (modular approach for better maintainability and scalability)
- **Authentication:** Firebase Auth

## Architecture
This project follows a multi-modular clean architecture approach, each module divided into three main layers:
- **Presentation Layer:** Utilizes Jetpack Compose for a reactive and efficient UI.
- **Domain Layer:** Contains business logic and use cases of the application.
- **Data Layer:** Manages data operations and provides data to the upper layers.

Each layer is implemented as a separate module to ensure separation of concerns and ease of testing.

## Getting Started
To get a local copy up and running follow these simple steps.

### Prerequisites
- Android Studio Arctic Fox | 2020.3.1 or higher
- Min SDK version 21

### Installation
1. Clone the repo
   ```sh
   git clone https://github.com/karolyguth/run-tracker

