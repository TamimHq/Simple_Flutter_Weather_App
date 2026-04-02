# 🌦️ Simple_Flutter_Weather_App

A simple and elegant Flutter weather application built using **GetX** for state management and navigation. This app fetches real-time weather data using the **OpenWeatherMap API**, includes a stylish **splash screen animation**, and demonstrates clean architecture with controller separation.

---

## 📱 Screenshots

<p align="center">
  <img src="assets/screenshots/splash.png" alt="Splash Screen" width="250"/>
  <img src="assets/screenshots/weather.png" alt="Waether Screen" width="250"/>

</p>


## 🚀 Features

- 🌐 Real-time weather info from [OpenWeatherMap](https://openweathermap.org/)
- 📦 GetX for state management, routing & DI
- 🎨 Clean UI with animation and gradient
- ⚡ Smooth transition from splash to main screen
- 📱 Responsive design with `SizeUtils` support
- 🔍 Error handling for invalid cities and network issues

---

## 🧱 Tech Stack

- **Flutter**
- **GetX**
- **HTTP package**
- **OpenWeatherMap API**

---

## 🛠️ Getting Started

### 1. **Clone the repository**

```bash
git clone https://github.com/TamimHq/Simple_Flutter_Weather_App.git
cd Simple_Flutter_Weather_App
```

### 2. **Install dependencies**

```bash
flutter pub get
```

### 3. **Add API Key**

Get your API key from [OpenWeatherMap](https://openweathermap.org/api), then open `weather_controller.dart` and replace:

```dart
final apiKey = 'YOUR_API_KEY';
```

with:

```dart
final apiKey = 'your_real_api_key';
```

### 4. **Run the app**

```bash
flutter run
```

---

## 🧪 Testing

To run widget tests:

```bash
flutter test
```
---

## 📂 Project Structure

```bash
lib/
├── main.dart
├── splash_screen.dart
├── weather_page.dart
├── controllers/
│   └── weather_controller.dart
│   └── splash_controller.dart
├── models/
│   └── weather_model.dart
├── widgets/
│   └── custom_image_view.dart
├── core/
│   └── utils/size_utils.dart
```

---



## 👤 Author

**Tamim Haque**  
📧 tamimhaque13@gmail.com

---

## 🙌 Acknowledgements

- [OpenWeatherMap API](https://openweathermap.org/)
- [GetX Package](https://pub.dev/packages/get)
- [Flutter](https://flutter.dev/)
