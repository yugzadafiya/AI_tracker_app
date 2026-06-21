# Calorie Tracker - AI Powered Health Companion

![Calorie Tracker Banner](app/src/main/res/drawable/branding_logo.png)

Calorie Tracker is a modern Android application designed to help users manage their health through intelligent food recognition, personalized BMI tracking, and comprehensive intake logging. Powered by the **Gemini AI API**, it can analyze nutritional content from photos in real-time.

## 🚀 Features

- **AI Food Recognition**: Simply take or upload a photo of your meal, and the app identifies nutritional values using Gemini AI.
- **Personalized Onboarding**: Set up your profile with name, age, weight, and height to get customized health metrics.
- **BMI Calculator**: Automatic BMI calculation based on your profile inputs.
- **History Tracking**: Keep a daily log of your food intake with visual history.
- **Modern UI/UX**: Premium design with health-focused color palettes (Green/Blue) and glassmorphism elements.

## 🛠️ Tech Stack

- **Lanuage**: Java
- **Networking**: OkHttp 3
- **JSON Parsing**: Gson
- **AI Engine**: Google Gemini API
- **Architecture**: Modern Android Component Architecture

## 📦 Getting Started

### Prerequisites

- Android Studio Koala/Ladybug or later.
- Android SDK 36 (target).
- A Google Gemini API Key.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/calorietracker.git
   ```
2. Open the project in Android Studio.
3. Sync Project with Gradle Files.

### API Key Configuration

To use the AI recognition feature, you must provide your own Gemini API key:

1. Create a `local.properties` file in the root directory (if it doesn't already exist).
2. Add your API key to the file:
   ```properties
   GEMINI_API_KEY=your_api_key_here
   ```
3. The app will automatically inject this key into the build configuration.

## 📸 Screenshots

*(Add screenshots of your app here to showcase its beautiful UI)*

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue. See [CONTRIBUTING.md](CONTRIBUTING.md) for more details.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
Made with ❤️ for better health.
