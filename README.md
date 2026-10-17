# 📱 PhishGuard — Android Mobile App

[![Build PhishGuard APK](https://github.com/LAKSHYACHAUHAN264/PhishGuard-Android-APK/actions/workflows/build-apk.yml/badge.svg)](https://github.com/LAKSHYACHAUHAN264/PhishGuard-Android-APK/actions/workflows/build-apk.yml)
[![Download APK](https://img.shields.io/badge/Download-APK-green?style=for-the-badge&logo=android)](https://github.com/LAKSHYACHAUHAN264/PhishGuard-Android-APK/releases/latest)
[![Android](https://img.shields.io/badge/Platform-Android_21+-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com)

Official Android mobile application for **PhishGuard — AI Email Phishing Detector**.

---

## 📥 Download the APK

Grab the latest ready-to-install APK directly from the Releases page:

👉 **[Download PhishGuard-v1.0.0.apk](https://github.com/LAKSHYACHAUHAN264/PhishGuard-Android-APK/releases/latest)**

### How to Install on Android:
1. Download `PhishGuard-v1.0.0.apk` onto your Android phone.
2. Tap the downloaded file in your Notification Bar or Downloads folder.
3. If prompted, allow **"Install unknown apps"** for your browser / file manager.
4. Tap **Install** and launch **PhishGuard**!

---

## ⚡ Features in Mobile App

- 🛡️ **Full AI Phishing Detector**: Paste any email body, sender, or subject to get immediate threat analysis.
- 🌐 **Connected to Live Cloud**: Powered by the deployed backend on Render (`https://scammer-project.onrender.com`).
- 🎨 **Adaptive Mobile UI**: Built with responsive cyber-neon glassmorphism aesthetics.
- 🚀 **Automated GitHub Actions CI/CD**: Every update to `main` compiles a new APK automatically!

---

## 🛠️ Project Structure

```
├── .github/workflows/
│   └── build-apk.yml         # GitHub Actions automatic APK compiler & release publisher
├── app/
│   ├── src/main/
│   │   ├── java/             # Android MainActivity WebView controller
│   │   ├── assets/           # Bundled web UI (index.html, style.css, app.js)
│   │   └── AndroidManifest.xml
│   └── build.gradle          # Android app module build configuration
├── build.gradle              # Root Gradle build script
└── settings.gradle           # Project settings
```

---

## 💻 Building from Source

### Using Android Studio:
1. Clone this repository:
   ```bash
   git clone https://github.com/LAKSHYACHAUHAN264/PhishGuard-Android-APK.git
   ```
2. Open the cloned folder in **Android Studio**.
3. Let Gradle sync and press **Run** ▶️ or select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.

---

<p align="center">
  Built with ❤️ by <a href="https://github.com/LAKSHYACHAUHAN264"><strong>LAKSHYACHAUHAN264</strong></a>
</p>
