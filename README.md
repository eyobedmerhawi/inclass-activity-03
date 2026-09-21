# 🍳 Kitchen Gadget Panel

A Flutter-based interactive kitchen control panel featuring tactile 3D buttons, live status updates, power calibration, and light/dark themes.

## ✨ Features

- **Kitchen Gadget Controls**: Four custom controls for BLEND, BAKE, CHILL, and SEAR.
- **3D Tactile Buttons**: Uses `GestureDetector`, `AnimatedContainer`, and opposing `BoxShadow` effects to simulate physical buttons.
- **Live State Management**: Tracks total button taps, current kitchen action, and power level using `setState()`.
- **Power Feedback**: The background changes when the power calibration level goes above 80%.
- **Light & Dark Mode**: Users can switch between light and dark themes from the app bar.
- **Interactive Power Slider**: Adjusts the power level from 0% to 100% in real time.
- **Reusable Components**: Uses a reusable `TactileButton` widget for all four kitchen controls.

## 🛠️ Tech Stack

- **Framework**: Flutter (Material 3)
- **Language**: Dart
- **Key Widgets**: `StatefulWidget`, `GestureDetector`, `AnimatedContainer`, `Slider`, `Wrap`