# temperature_converter

```markdown

## Overview

The **Temperature Converter App** is a Flutter-based mobile application that allows users to convert temperatures between Fahrenheit and Celsius. The app provides a simple and user-friendly interface to enter a temperature value and switch between conversion modes.

## Features

- Convert temperatures between **Fahrenheit to Celsius** and **Celsius to Fahrenheit**
- Dynamic UI to switch between conversion modes
- Input validation to handle empty or invalid inputs
- Detailed conversion history tracking
- Aesthetic UI with Material Design and color gradients

## Technologies

- **Flutter**: A framework for building natively compiled applications for mobile from a single codebase.
- **Dart**: The programming language used by Flutter.
- **Material Design**: Flutter’s design system to create visually consistent UIs across platforms.

## Installation

To run this application locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/temperature-converter-app.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd temperature-converter-app
   ```
3. **Install dependencies**:
   ```bash
   flutter pub get
   ```
4. **Run the application**:
   ```bash
   flutter run
   ```

## Code Structure

The main code for the application is structured into the following components:

### `TemperatureConverterApp`

This is the root widget of the app. It defines the **MaterialApp** with the app's theme and provides navigation to the main **TemperatureConverter** widget.

### `TemperatureConverter`

This widget handles the UI for input, mode selection, and the display of the converted result. It also maintains the conversion history in a list.

### `TemperatureConverterState`

This is the **State** class that manages the app's logic for conversion between Fahrenheit and Celsius. It also stores the input value and updates the conversion history.

## Example Usage

1. Enter the temperature value in the input field.
2. Choose the conversion mode by tapping either the **F to C** or **C to F** button.
3. Press the **Convert** button to see the result.
4. The converted value will be displayed along with a detailed history of previous conversions.

## Screenshots

### First View ### Convert 30°F to C ### Convert 30°C to F
![First View](https://github.com/Ngum12/Temperature_Conversion-app/raw/master/First%20view.png) 

### Convert 30°F
![Convert 30°F to C](https://github.com/Ngum12/Temperature_Conversion-app/raw/master/Convert%2030F%20to%20C.png) 

### Convert 30°C to F
![Convert 30°C to F](https://github.com/Ngum12/Temperature_Conversion-app/raw/master/convert%2030%20C%20to%20F.png)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any queries, please reach out to:

- **Your Name**: [d.ngum@alustudent.com](mailto:your-email@example.com)
- GitHub: [Ngum12](https://github.com/your-github-username)
```


A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
