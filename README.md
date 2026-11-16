📺 CleanYourTV – Xiaomi MiTV-AXSO0 Custom Edition

"Android TV" (https://img.shields.io/badge/Platform-Android%20TV-green)
"Device" (https://img.shields.io/badge/Device-Xiaomi%20MiTV--AXSO0-blue)
"Android" (https://img.shields.io/badge/Android-9-orange)
"Customization" (https://img.shields.io/badge/Customization-Personal%20Build-purple)

A cleaner, modern and personalized Android TV experience based on CleanYourTV, customized for the Xiaomi MiTV-AXSO0 (Dangal).

The objective is simple: create a minimal, elegant, Apple TV-inspired home screen while preserving essential streaming, connectivity and smart TV functionality.

✨ Features

Feature| Configuration
Frosted Glass Dock| ✅ Enabled
Dock Background Band| ✅ Enabled
Ambient Glow| ✅ Enabled
Dynamic App Glow| ❌ Disabled
Wi-Fi Status Indicator| ✅ Enabled
App Library| ✅ Enabled
App Library Home Pill| ✅ Enabled
Personalized Greeting| Vicky
Home Screen Columns| 5

🎬 Custom App Dock

The home screen dock is configured with:

1. YouTube
2. Netflix
3. Prime Video
4. Google Play Store
5. Empty slot for future customization

📱 Target Device Specifications

Specification| Value
Device| Xiaomi MiTV-AXSO0
Codename| Dangal
Android Version| 9
SDK Version| 28
Build ID| PI.6036
Platform| Amlogic

🛡️ Preserved Functionality

The configuration is designed to preserve important services:

- YouTube, Netflix and Prime Video
- Google Play Store
- Google Assistant
- Chromecast
- Miracast
- Live TV and input services
- Firmware update services

🖼️ Screenshots

Add screenshots of your actual TV home screen here after installation.

Suggested screenshots:

- Home screen and personalized greeting
- Frosted Glass Dock
- App Library
- Wi-Fi status indicator

⚙️ Installation

Requirements

- Windows PC
- ADB Platform Tools
- Android SDK and Java 17
- Xiaomi TV with ADB debugging enabled
- Network connectivity between PC and TV

Build and install

From the launcher's directory, run PowerShell:

powershell.exe -NoProfile -ExecutionPolicy Bypass -File ".\build-and-install.ps1" -TvHost YOUR_TV_IP -StockLauncher com.google.android.tvlauncher

Replace "YOUR_TV_IP" with your television's local IP address.

Review the project's installation instructions and backup your device configuration before proceeding.

📁 Project Structure

CleanYourTV-Xiaomi-MiTV-AXSO0/
│
├── launcher/
│   ├── app/
│   │   └── src/main/
│   │       ├── java/
│   │       └── res/
│   │           ├── layout/
│   │           └── values/
│   │               ├── config.xml
│   │               └── strings.xml
│   │
│   └── build-and-install.ps1
│
├── README.md
└── LICENSE

⚠️ Disclaimer

This is a personal customization of the CleanYourTV project.

- Compatibility is currently targeted at Xiaomi MiTV-AXSO0.
- Other device models may require different configurations.
- Back up your original settings before changing system applications.
- Do not disable essential Android TV, Google, Chromecast, Miracast or firmware services.
- This repository is not an official Xiaomi or CleanYourTV release.

🙏 Credits

Based on the original CleanYourTV project.

Please refer to the upstream repository for original authorship, licensing and acknowledgements.

All original contributors retain credit for their work.