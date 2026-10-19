# Countries Flutter App

Countries Flutter App is a Flutter application that consumes the REST Countries API to retrieve and display information about countries.

The application displays country names along with their capitals, continents, and flags. It also provides functionality to search and sort countries based on their name, capital, or continent.

## Prerequisites

Before running the application, make sure the following are installed and configured on your system:

- Flutter SDK
- Dart SDK
- Android Studio or another supported IDE
- An Android/iOS emulator or a physical device, if running the mobile application

The project was originally developed using Flutter 3.10.1.

## API

The application uses the REST Countries API to retrieve country information.

API:

https://restcountries.com/

## Local Setup

Clone the repository:

```bash
git clone https://github.com/RaphaelRat/flutter-restapi-country.git
````

 Navigate to the project directory:

```
cd flutter-restapi-country
```

 Install the project dependencies:

```
flutter pub get
```

 Verify that Flutter is correctly configured:

```
flutter doctor
```

 Run the application:

```
flutter run
```

 For web development, the application can also be run using:

```
flutter run -d chrome
```

 ## Features

 - Displays a list of countries.
- Displays country capital, continent, and flag.
- Sorts countries alphabetically by name, capital, or continent.
- Allows users to search for countries by name, capital, or continent.
- Supports Android, iOS, and web platforms.

 ## Project Repository

 The source code for this project is available on GitHub:

 https://github.com/RaphaelRat/flutter-restapi-country.git

 ## License

 This project is provided as an example Flutter application demonstrating how to consume a REST API.
