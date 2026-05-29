# 📱 Urban Lunch: Mobile Application Quality Assurance

Backend-integrated mobile app testing and environment configuration for the Urban Lunch (V2) platform. This repository focuses on the end-to-end functional validation of final checkout and delivery flows, execution of an advanced 31-item checklist across 6 core product sections, and interface integrity auditing (Figma vs. Code) using Android Studio emulators.

---

### 🛠️ Technical Ecosystem & Tools
* **Emulation & IDE:** Android Studio (Android Virtual Device - AVD)
* **OS Interactivity:** Command Line Interface via Android Debug Bridge (ADB) console
* **Requirements Source of Truth:** Figma Prototypes & Product Specification Documents

---

### 📊 Performance & Defect Analytics
* **Execution Metrics:** 31 Test Cases Audited (26 Pass ✅ / 5 Fail ❌)

| Section / Core Flow | Total Cases | Status |
| :--- | :---: | :---: |
| 1. Pickup Point Selection | 4 | Pass ✅ |
| 2. Dish Selection Flow | 11 | Pass ✅ |
| 3. Order Confirmation | 6 | Critical Fails ❌ |
| 4. Order Tracking & Pickup Screen | 4 | Pass ✅ |
| 5. Order Dispatch & Status Updates | 4 | Pass ✅ |
| 6. Error Notification Handlers | 2 | Fail ❌ |

---

### 📂 Attached Artifacts & Test Sheets
* 📊 **[Attached Sheet: Checklist_Sprint6_Mobile_Urban_Lunch.xlsx](Checklist_Sprint6_Mobile_Urban_Lunch.xlsx)** – *Comprehensive 31-item QA test suite covering functional requirements, interface validation, and boundary conditions.*

---

### 🚨 Detailed Defect Log (LUN-1)
* **Bug Title:** [Crash] App closes unexpectedly upon denying geolocation permissions on the onboarding screen.
* **Severity/Priority:** Critical / Highest
* **Evidence:** 🎬 **[Watch Bug Execution Clip: Bug_Location_DENY.mp4](Bug_Location_DENY.mp4)**
* **Environment:** Android Studio Virtual Device (AVD) | Android 9.0 (Pie) | API Level 28

#### Steps to Reproduce:
1. Open the Urban Lunch mobile application on the emulator.
2. Wait for the system location permission pop-up to appear (*"Allow Urban Lunch to access this device's location?"*).
3. Click on the **DENY** button.

#### Results:
* **Expected Result:** The application handles the denial gracefully, displays an error banner stating location is required, and remains functional.
* **Actual Result:** The application crashes immediately, forcing a hard close back to the Android home screen.

---

### 🎥 Full Live Verification Documentation
* 🎬 **[Watch Full Mobile QA Execution Video](Git_Hub_APPmovil.mp4)** – *Comprehensive video demonstration detailing local environment sync, terminal console commands, and live device emulation tracking.*
