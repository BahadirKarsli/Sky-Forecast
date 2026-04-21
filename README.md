<div align="center">
  <h1>🌤️ Sky Forecast</h1>
  <p>A cross-platform, real-time weather application providing accurate daily and weekly forecasts based on your location.</p>
</div>

<br/>

## 🎯 About the Project

**Sky Forecast** is a comprehensive weather application designed to deliver real-time meteorological data to users. Developed using **Flutter/Dart**, it offers a seamless cross-platform experience (Android, iOS, Web, Desktop). By leveraging geolocation and integrating multiple reliable weather APIs, the app instantly displays crucial data such as temperature, humidity, wind speed, and extended forecasts tailored specifically to your current location.

## ✨ Key Features

- **Real-Time Weather Data:** Instant access to current temperature, humidity levels, and wind speed.
- **Extended Forecasts:** Detailed daily and weekly weather predictions.
- **Location Auto-Detection:** Automatically detects your current location via GPS to provide localized weather updates.
- **Multi-API Integration:** Fetches highly accurate data by combining endpoints from [Open-Meteo](https://open-meteo.com/) and [OpenWeatherMap](https://openweathermap.org/).
- **Cross-Platform:** Built with Flutter, supporting Android, iOS, Windows, macOS, Linux, and Web environments.

## 📂 Repository Structure

The core files and directories in this repository are structured according to standard Flutter architecture:

```text
├── android/         # Native Android project files
├── ios/             # Native iOS project files
├── lib/             # Main Dart source code (UI, logic, API calls)
├── linux/           # Native Linux project files
├── macos/           # Native macOS project files
├── web/             # Web compilation files
├── windows/         # Native Windows project files
├── assets/          # Icons, images, and other static assets
├── pubspec.yaml     # Flutter dependencies and project configuration
└── README.md        # Project documentation
```

## 🛠️ Technologies Used

- **Framework:** Flutter
- **Programming Language:** Dart
- **APIs:** - [Open-Meteo API](https://open-meteo.com/) (Weather & Geocoding)
  - [OpenWeatherMap API](https://openweathermap.org/) (Supplementary Weather Data)

## 🚀 Installation & Setup

To compile and run the application from the source code, please follow these steps:

### 1. **Install Prerequisites:**
   - Install the [Flutter SDK](https://docs.flutter.dev/get-started/install).
   - Install an IDE such as [Android Studio](https://developer.android.com/studio) or VS Code with the Flutter and Dart extensions.
   - Install the [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html).

### 2. **Clone the Repository:**
   ```bash
   git clone https://github.com/BahadirKarsli/Sky-Forecast.git
   cd Sky-Forecast
   ```

### 3. **Fetch Dependencies:**
   ```bash
   flutter pub get
   ```

### 4. **Run the Application:**
   Connect your physical device or launch an emulator/simulator, then execute:
   ```bash
   flutter run
   ```

## 💻 Usage Instructions

### 1. Launch the application on your target device.
### 2. When prompted, **grant location permissions** so the app can pinpoint your current coordinates.
### 3. The dashboard will automatically populate with real-time weather conditions and the upcoming forecast for your area.

## 🤝 Contributing

Contributions, bug reports, and feature requests are always welcome! Feel free to open an **Issue** or submit a **Pull Request** to help improve the project.
