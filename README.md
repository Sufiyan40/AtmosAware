AtmosAware - Weather Application
🌦 Introduction
AtmosAware is a weather application built using Kotlin and Gradle. The app fetches and displays weather information for a specified location, providing users with real-time weather updates.

✅ Prerequisites
Before running the application, ensure the following are installed:

Java Development Kit (JDK) (version 8 or higher)
Android Studio
Gradle (optional if Android Studio handles Gradle builds)
🚀 Steps to Execute the Application
1️⃣ Clone the Repository
Use the following commands to clone the repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/AtmosAware.git
cd AtmosAware
2️⃣ Open in Android Studio
Launch Android Studio.
Select File > Open and navigate to the cloned project folder.
Wait for Android Studio to sync the Gradle files. This may take a few minutes.
3️⃣ Configure the API Key
Open the res/values/strings.xml file.
Add your weather API key as follows:
xml
Copy code
<string name="api_key">YOUR_API_KEY</string>
Replace YOUR_API_KEY with a valid API key from a weather service (e.g., OpenWeatherMap).
4️⃣ Run the Application
Connect an Android device or launch an emulator.
Click the Run button in Android Studio, or use the shortcut Shift + F10.
5️⃣ Download the App on Mobile (Optional)
Build the APK file:
Navigate to Build > Build Bundle(s)/APK(s) > Build APK in Android Studio.
Use a QR code generator to create a scannable link for the APK file.
Scan the QR code with your mobile device to download and install the app.
6️⃣ View Weather Information
Open the app on your mobile or emulator.
Enter the desired city or location in the app.
The app will fetch and display the weather data.
