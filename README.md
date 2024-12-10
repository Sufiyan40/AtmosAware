# AtmosAware - Weather Application

## 🌦 Introduction
**AtmosAware** is a weather application built using **Kotlin** and **Gradle**. The app fetches and displays weather information for a specified location, providing users with real-time weather updates.

---

## ✅ Prerequisites
Before running the application, ensure the following are installed:
1. **Java Development Kit (JDK)** (version 8 or higher)
2. **Android Studio**
3. **Gradle** (optional if Android Studio handles Gradle builds)

---

## 🚀 Steps to Execute the Application

### 1️⃣ Clone the Repository
Use the following commands to clone the repository to your local machine:
```bash
git clone https://github.com/your-username/AtmosAware.git
cd AtmosAware
```
### 2️⃣ Open in Android Studio
 Launch Android Studio (no specific CLI command, follow GUI steps):
 1. Open Android Studio.
 2. Navigate to File > Open.
 3. Select the cloned project folder and wait for Gradle to sync.

### 3️⃣ Configure the API Key
 Open the following file in a text editor or via Android Studio:
```
res/values/strings.xml
```
 Add your weather API key in the following format:
 ```
<string name="api_key">YOUR_API_KEY</string>
```
 Replace YOUR_API_KEY with a valid API key from a weather service (e.g., OpenWeatherMap).

### 4️⃣ Run the Application
 Connect your Android device via USB or use an emulator.
 In Android Studio, click the Run button or use the shortcut: ```Shift + F10```

