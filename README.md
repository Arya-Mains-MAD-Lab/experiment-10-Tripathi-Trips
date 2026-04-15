# Flutter Image Handling App

## Overview

This project is a Flutter application that demonstrates how to display and handle images from the internet. It uses `MediaQuery` to make the image responsive based on the screen size.

The app showcases basic image loading and responsive UI design in Flutter.

---

## Features

* Load and display image from a network URL
* Responsive image sizing using `MediaQuery`
* Maintain aspect ratio with `BoxFit`
* Simple and clean user interface

---

## Technologies Used

* Flutter
* Dart
* Material UI components

---

## Project Structure

* `main.dart`

  * Contains the entire application logic
  * Includes:

    * `MyApp`: Root widget
    * `MediaPage`: Handles image display and responsiveness

---

## How It Works

1. The app launches with the MediaPage screen.
2. `MediaQuery` is used to get screen dimensions.
3. The image is loaded from a network URL.
4. The width and height of the image are adjusted dynamically:

   * Width: 80% of screen width
   * Height: 30% of screen height
5. The image is displayed with proper scaling using `BoxFit.contain`.

---

## How to Run

1. Install Flutter on your system.
2. Create a new Flutter project or replace the content of `main.dart` with this code.
3. Run the following command:

   ```
   flutter run
   ```
4. Launch the app on an emulator or physical device.

---

## Future Improvements

* Add image loading indicators
* Handle network errors
* Support local images (assets)
* Add image gallery functionality
* Improve UI/UX design

---

## Student Information

* Name: Sidharth Tripathi
* Roll Number: 23EACCA047
* Branch: Al
* Batch: BETA
