
# Footstep Counter App

The **Footstep Counter App** is a Flutter application that tracks your daily steps using your device's accelerometer. It calculates the distance traveled, calories burned, and provides an average of your daily steps.

## Features

- **Real-time Step Tracking**: 
  - Utilizes the device's built-in accelerometer to monitor movements and count steps accurately.
- **Calories Burned**: 
  - Estimates the number of calories burned based on the steps taken, helping you keep track of your fitness goals.
- **Distance Covered**: 
  - Converts the step count into miles, giving you a clear idea of how far you've walked.
- **Daily Average Steps**: 
  - Calculates and displays the average steps taken daily, providing insights into your activity levels over time.
- **Persistent Data**: 
  - Uses `shared_preferences` to save and retrieve step counts across sessions, ensuring continuity in your tracking data.

## Screenshots

*Include screenshots of your app here to visually represent the UI and functionality.*

## Installation

Follow these steps to get the app running on your local machine:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/footstep-counter.git
   cd footstep-counter
   ```

2. **Install dependencies**:
   Run the following command to install the necessary Flutter packages.
   ```bash
   flutter pub get
   ```

3. **Run the app**:
   Launch the app on an emulator or a physical device using:
   ```bash
   flutter run
   ```

## Usage

1. **Opening the App**: Launch the app to start tracking your steps automatically.
2. **Switching Views**: Use the bottom navigation bar to switch between different views, such as today's steps, plans, and daily averages.
3. **Real-time Updates**: The app updates the step count, distance, calories burned, and duration in real-time as you move.

## Code Explanation

- **`dashboard.dart`**: 
  - Contains the main UI logic, including the step counter, distance, calories, and duration calculations.
  - Uses `StreamBuilder` to listen for real-time accelerometer data.
- **`footCounter.dart`**: 
  - A simpler version focusing on displaying the real-time step count.
- **Shared Preferences**: 
  - Used for saving and retrieving the previous distance to maintain continuity across app sessions.

## Dependencies

The app relies on the following Flutter packages:

- [`sensors_plus`](https://pub.dev/packages/sensors_plus): For accessing the device's sensors, like the accelerometer.
- [`shared_preferences`](https://pub.dev/packages/shared_preferences): For storing small amounts of data locally.
- [`google_fonts`](https://pub.dev/packages/google_fonts): For using custom Google fonts in the app's UI.

## Contribution Guidelines

We welcome contributions! Here's how you can help:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test thoroughly.
4. Submit a pull request explaining your changes.

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute the code, as long as the original license and copyright notice are retained.

## Contact

For feedback, questions, or suggestions, please contact:
- GitHub: [yourusername](https://github.com/yourusername)
- Email: your.email@example.com


