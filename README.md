# FoodApp
MyApp is an Android application built using the principles of clean architecture and MVVM design pattern. It fetches data from a remote server using Retrofit and displays it in a RecyclerView. Dependency injection is handled with Hilt.

# Modules
The app is organized into the following modules:

- app: Contains the main application module. This is where the UI components, such as activities and fragments, are implemented. It depends on the presentation module.
presentation: Implements the presentation layer of the app. It contains ViewModels and interfaces for interacting with the UI. It depends on the domain module.
- domain: Implements the domain layer of the app. It contains business logic and use cases. It depends on the data module.
- data: Implements the data layer of the app. It handles data retrieval from the remote server using Retrofit and provides repositories for accessing the data. It depends on the remote module.
- remote: Implements the remote data source module. It defines APIs and data models used for communication with the remote server.
Dependencies
The app uses the following major dependencies:

- Hilt: For dependency injection. It simplifies the setup and management of dependencies
- Retrofit: For making network requests. It provides a convenient way to interact with RESTful APIs.
- RecyclerView: For displaying a list of items efficiently. It is used to present the fetched data in a scrollable list.
- ViewModel: A part of the Android Architecture Components. It helps in managing UI-related data and handling lifecycle events.
# Setup
To run the app, follow these steps:

- Clone the repository.
- Open the project in Android Studio.
- Build the project to resolve the dependencies.
- Run the app on an emulator or a physical device.
# Configuration
The app requires an internet connection to fetch data from the remote server. Make sure you have a stable internet connection during app usage.

# Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.
