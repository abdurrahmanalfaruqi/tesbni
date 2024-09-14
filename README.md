# TestBni

TestBni is a Flutter demo application designed to monitor and display realtime data stream per second from [EODHD API](https://eodhd.com/financial-apis/new-real-time-data-api-websockets). The app has been tested on iOS (iPhone X) and Android (API 34 and latest).

This app uses the BLoC (Business Logic Component) architecture to separate business logic from the UI. BLoC allows the app to handle real-time data streams reactively, ensuring that the UI updates based on state changes.

## Prerequisites
 - Flutter SDK version 3.22.3
 - Dart version 3.4.4

## Installation

To get started with eodhd_monitor, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/abdurrahmanalfaruqi/tesbni.git
    ```
2. **Navigate to the project directory:**
    ```sh
    cd eodhd_monitor
    ```
3. **Install dependencies:**
    ```sh
    flutter pub get
    ```
4. **Run the application:**
    ```sh
    flutter run
    ```
