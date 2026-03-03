# 🐟 Smart IoT Fish Feeder

> Remote-controlled automated feeding system with real-time monitoring and cloud synchronization.

---

## ✨ Project Snapshot

**Role:** Full‑stack IoT Engineer  
**Hardware:** ESP32, Servo Motor  
**Frontend:** Next.js Dashboard  
**Backend & Cloud:** Firebase  
**Focus Areas:** IoT · Web Control · Mechanical Design

---

## 🧩 The Problem

Pet owners often worry about feeding schedules when traveling or working long hours.  
Basic timer-based feeders:

- Cannot be monitored remotely
- Offer no feeding verification
- Risk overfeeding due to mechanical jams
- Lack real-time control

A smarter, connected, and fail-safe system was needed.

---

## 💡 The Solution

Designed and developed a **Wi‑Fi enabled automated fish feeder** powered by ESP32, integrated with a responsive web dashboard.

The system allows:

- Remote feeding from anywhere
- Scheduled feeding times
- Real-time status monitoring
- Safe portion control

---

## ⚙️ Engineering Approach

### 🧠 Firmware Logic (ESP32)

- Controlled servo-based dispensing mechanism
- Implemented strict anti-overfeeding safeguards
- Designed jam-detection logic
- Integrated Wi‑Fi communication module
- Ensured stable operation under continuous uptime

### 🌐 Cloud Synchronization

- Firebase real-time database for feeding schedules
- Status logs stored in cloud
- Two-way sync between dashboard and device

### 💻 Web Dashboard (Next.js)

- Mobile-responsive interface
- Manual feeding trigger
- Schedule configuration panel
- Device status display
- Clean, minimal UI

### 🔩 Mechanical Design

- Custom dispensing mechanism
- Calibrated rotation angles for portion control
- Reduced servo stress for longevity

---

## 🚀 Key Features

- 📡 Remote feeding via browser
- ⏰ Scheduled feeding automation
- 🔒 Anti-overfeeding firmware logic
- 📊 Real-time device monitoring
- 🏠 Seamless home Wi‑Fi integration
- 📱 Mobile-friendly control dashboard

---

## 📊 Results & Impact

- Reliable remote feeding with cloud verification
- Eliminated overfeeding incidents via strict firmware control
- Real-time monitoring reduced anxiety for pet owners
- Stable long-term deployment on home Wi‑Fi networks

---

## 🏗️ System Flow

```
[User Dashboard - Next.js]
            ↓
      Firebase Database
            ↓
         ESP32 Wi-Fi
            ↓
     Servo Dispensing Motor
            ↓
       Fish Feeding Action
```

---

## 📂 Suggested Repository Structure

```
smart-iot-fish-feeder/
│
├── firmware/
│   ├── main.cpp
│   ├── servo_control.cpp
│   ├── wifi_manager.cpp
│   └── config.h
│
├── web-dashboard/
│   ├── pages/
│   ├── components/
│   └── firebase-config.js
│
├── hardware/
│   ├── circuit_diagram.png
│   └── mechanical_design.md
│
└── README.md
```

---

## 🔮 Future Enhancements

- Camera integration for feeding verification
- Portion-size calibration via mobile app
- Push notifications
- Battery backup system
- Usage analytics dashboard

---

## 🖼️ Preview

_Add project screenshots or demo GIF here._

---

## 🤝 Work With Me

Interested in building connected devices or intelligent IoT systems?  
Let’s collaborate.

---

## 👤 Author

**Jishnu Mahanta**  
Full‑stack & IoT Engineer  
Building intelligent systems & calm UX.

---

## 📜 License

MIT License 
