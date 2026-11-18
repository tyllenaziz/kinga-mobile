this is the installation link  https://expo.dev/accounts/tyllen001/projects/kinga-pest-control/builds/f584abe6-ded7-4c71-a986-12799741f1ce

# 📱 Kinga - Mobile App

A cross-platform mobile application built for farmers to detect crop pests in real-time using AI. Built with React Native and Expo.

## ✨ Key Features
*   **📸 Scan & Analyze:** Capture images via Camera or Gallery to detect pests instantly.
*   **🗣️ Bilingual Support:** Full support for **English** and **Swahili**, including Text-to-Speech audio advice.
*   **🔐 User Accounts:** Login, Signup, and OTP Verification.
*   **👨‍🌾 Expert Support:** Direct "Chat with Expert" button (WhatsApp Integration).
*   **📜 History:** View past scans and cloud-stored records.
*   **📚 Detailed Info:** View Causes, Effects, and Solutions for every pest.

## 🛠️ Tech Stack
*   **Framework:** React Native (Expo)
*   **Language:** TypeScript / JavaScript
*   **UI Library:** React Native Paper
*   **Networking:** Axios
*   **Build Tool:** EAS (Expo Application Services)

## 🚀 How to Run

1.  **Clone the repository**
    ```bash
    git clone https://github.com/YOUR_USERNAME/kinga-mobile.git
    cd kinga-mobile
    ```

2.  **Install Dependencies**
    ```bash
    npm install
    ```

3.  **Start the App**
    ```bash
    npx expo start
    ```
    *Scan the QR code with the **Expo Go** app on your phone.*

4.  **Build Android APK**
    ```bash
    npm install -g eas-cli
    eas build -p android --profile preview
    ```

## 📂 Configuration
The app connects to the Kinga Backend hosted on Render. You can change the `API_URL` in `app/(tabs)/index.tsx`.
