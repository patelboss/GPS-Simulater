# 🚀 Base App — GPS Simulation Tool

> A lightweight Android app to simulate GPS location for testing, development, and controlled location workflows.

---

## 📥 Download

👉 **[⬇️ Download Latest Release](https://github.com/patelboss/GPS-Simulater/releases/latest)**

---

## 🧭 Overview

Base App is designed to **simulate GPS locations on Android devices**, allowing you to override your device’s real location with custom coordinates.

Whether you're testing location-based apps, debugging navigation flows, or experimenting with geo-based features — this tool gives you full control.

---

## 🎯 Why this app exists

This project started with a simple frustration:

> Testing GPS-based features on Android is slow, inconsistent, and often unreliable.

Switching locations manually, relying on real movement, or using unstable tools just wastes time.

So the goal became clear:
- ⚡ Fast location testing  
- 🎯 Accurate coordinate control  
- 🧪 Reliable simulation behavior  
- 📱 Works across old and new Android versions  

---

## ✨ Features

- 📍 **Custom GPS Simulation**  
  Enter any latitude & longitude and simulate instantly  

- 🧭 **Compass Integration**  
  Helps align direction-based testing  

- 🗺️ **Map Interaction (planned/improving)**  
  Visual understanding of location  

- ▶️ **Start / Stop Controls**  
  Toggle simulation easily  

- 📊 **Live Status Feedback**  
  Know exactly what the app is doing  

- ⚡ **Lightweight & Fast**  
  No unnecessary bloat  

---

## 🏗️ Architecture

### 🔹 Core Components

- **Mock Location Engine**
  - Uses Android MockProvider to override GPS  
  - Requires Developer Options → *Allow mock locations*  

- **Foreground Service**
  - Keeps simulation running in background  
  - Prevents Android from killing the process  

- **User Interface**
  - Coordinate input (Latitude / Longitude)  
  - Start / Stop controls  
  - Status display system  

- **Validation Layer**
  - Prevents crashes from invalid input  
  - Handles edge cases safely  

---

## ⚙️ Technical Details

- 📦 Multi-dex enabled  
- 🔐 Proper APK signing (V1 + V2 + V3)  
- 🧩 Compatible with Android 5.0+  
- 📡 Uses `LocationManager` for injection  

---

## 🚧 Challenges We Solved

This wasn’t just plug-and-play. Some real issues we tackled:

- ❌ App crashes due to invalid coordinates  
- 🔄 Improper lifecycle handling (GPS getting stuck)  
- 📍 Mock provider not updating correctly  
- 🧠 UI not reflecting actual state  
- ⚠️ Compatibility across Android versions  

Each of these shaped the current stable version.

---

## ⚠️ Requirements

Before using the app:

1. Enable **Developer Options**
2. Enable:
   - ✔️ *Allow mock locations*  
   OR  
   - ✔️ Select this app as mock location provider  

---

## 📲 Installation

1. Download APK from releases  
2. Enable **Install unknown apps**  
3. Install and open  

---

## 🔮 Roadmap

- 🎨 UI improvements  
- 🗺️ Interactive map selection  
- 📍 Saved locations  
- ⚡ Performance optimization  
- 📦 AAB support for Play Store  

---

## 🤝 Contributing

Contributions, suggestions, and feedback are welcome.

Feel free to:
- Open issues  
- Suggest features  
- Report bugs  

---

## ⚠️ Disclaimer

This app is intended for:
- Testing  
- Development  
- Educational purposes  

Use responsibly. Misuse may violate terms of other apps/services.

---

## ❤️ Final Note

This project started small — just trying to make GPS testing easier.  
But step by step, debugging errors, fixing crashes, and improving logic… it turned into something solid.

If it helps you even a little — it did its job.

---

**Version:** 1.0.0  
**Tag:** base_app_1.0
