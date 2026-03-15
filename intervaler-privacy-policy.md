# Privacy Policy — Intervaler AI

**Last updated: March 15, 2026**

Intervaler AI ("the app") is a Wear OS interval training app with an optional Android companion app. This policy explains what data the app collects, how it is used, and your rights regarding that data.

---

## 1. Data We Collect

All data collected by Intervaler AI is stored **locally on your device only**. We do not operate any servers, and no personal data is transmitted to us or any third party.

### Heart Rate
- **What**: Heart rate measurements taken during workouts.
- **How**: Collected via the Wear OS Health Services API (requires the Body Sensors and Read Heart Rate permissions).
- **Why**: To display live heart rate during workouts and calculate average heart rate per session.
- **Where stored**: On your Wear OS watch in local app storage. A summary (average heart rate) is saved to your workout history.

### Location (GPS)
- **What**: GPS speed readings taken during workouts.
- **How**: Collected via the device GPS (requires the Precise Location permission).
- **Why**: To display your current speed during outdoor workouts (e.g., running pace).
- **Where stored**: Speed data points are stored locally on your device. Raw GPS coordinates are never stored or recorded.

### Body Profile
- **What**: Biological sex, body weight, and height.
- **How**: Entered manually by you in the Profile screen.
- **Why**: To estimate calories burned during workouts using MET-based calculations.
- **Where stored**: Locally on your Wear OS watch. Never transmitted.

### Workout History
- **What**: Workout name, date, duration, rounds completed, average heart rate, and estimated calories burned.
- **Why**: To display your past sessions in the History screen.
- **Where stored**: Locally on your Wear OS watch (capped at 50 records).

### AI Insights
- **What**: A text summary generated after each workout based on your workout data (name, duration, rounds, heart rate).
- **How**: Generated entirely on your Android phone using an on-device language model (Google Gemma 2B via MediaPipe). No workout data is sent to the internet or any external AI service.
- **Where stored**: Locally on your Android phone and Wear OS watch (capped at 20 insights each). Data is transferred between your watch and phone via the local Wearable Data Layer (Bluetooth), never over the internet.

---

## 2. Data We Do NOT Collect

- We do not collect your name, email address, or any account information.
- We do not use analytics or crash reporting SDKs.
- We do not display advertisements.
- We do not share any data with third parties.
- We do not transmit any data over the internet.

---

## 3. Permissions Used

| Permission | Purpose |
|------------|---------|
| Body Sensors | Read heart rate from the Wear OS sensor during workouts |
| Health Read Heart Rate | Read heart rate via the Health Services API |
| Precise Location | Read GPS speed during outdoor workouts |
| Post Notifications | Show a persistent notification while a workout is active |
| Vibrate | Deliver haptic feedback at interval transitions |

---

## 4. Data Retention and Deletion

- Workout history is automatically capped at 50 records (oldest deleted first).
- AI insights are capped at 20 entries per device.
- You can clear all stored data at any time by uninstalling the app, which removes all local app storage.

---

## 5. Children's Privacy

Intervaler AI is not directed at children under 13. We do not knowingly collect data from children.

---

## 6. Changes to This Policy

If we make material changes to this policy, we will update the "Last updated" date above. Continued use of the app after changes constitutes acceptance of the revised policy.

---

## 7. Contact

If you have questions about this privacy policy, please open an issue at:
[github.com/matanyaasis288/intervaler-privacy-policy](https://github.com/matanyaasis288/intervaler-privacy-policy)
