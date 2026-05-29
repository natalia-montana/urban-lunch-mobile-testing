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
* **Core Defect Logs:** * 💵 **Financial Calculation:** Discovered checkout logic failure omitting delivery fees from the final balance calculation.
  * 🎨 **UI Interface Integrity:** Identified overlapping text fields on dish/brand layouts, violating visual requirements.
  * ⏳ **Navigation Friction:** Uncovered a 6-second UI freeze post-confirmation lacking any loading indicators or UX feedback.

---

### 🎥 Live Verification Documentation
* 🎬 **[Watch Live Mobile QA Execution Video](https://github.com/natalia-montana/urban-lunch-mobile-testing)** – *Comprehensive video demonstration detailing local environment sync, terminal console commands, and live device emulation tracking.*
