# Flutter TV Launcher 

A lightweight, custom launcher for Android TV (tested on Xiaomi TV), built with Flutter. Designed to provide a clean interface, free from bloatware, and optimized exclusively for use with a remote control.

## Key Features
* 🎮 **D-Pad Navigation:** Full focus management using the remote control's directional arrows.
* 🚀 **App Launching:** Access and launch both system and third-party installed applications.
* ⚙️ **System Settings:** Direct shortcut to trigger the native settings intent (Wi-Fi, Bluetooth).
* 🪶 **Zero Distractions:** No sponsored carousels or recommended apps—just your own library.

## Development and Testing

1. Ensure your Flutter environment is correctly configured.
2. Enable **Network Debugging (or USB Debugging)** via the TV's Developer Options.
3. Connect to the TV using ADB:
   ```bash
   adb connect INDIRIZZO_IP_TV:5555
