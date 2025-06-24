# 🎧 BLEAudioConnect

A modern **SwiftUI** iOS app that simulates discovering and inspecting nearby **Bluetooth audio devices**. Built with a clean MVVM architecture, this project is designed to work seamlessly **on the iOS Simulator** with mock BLE and REST APIs.

---

## 🧠 Key Features

- ✅ Native **iOS Development** in **Swift**
- ✅ Simulated **Bluetooth BLE** scanning (GATT-ready structure)
- ✅ Clean **MVVM architecture** with Combine
- ✅ Multithreading using `DispatchQueue`
- ✅ Simulated **REST API** (Device Info fetch)
- ✅ **Simulator-compatible** with mocked peripherals
- ✅ Easy to extend for real `CoreBluetooth` integration

---

## 💡 Architecture

BLEAudioConnect/
├── Models/ → BLEDevice, Peripheral, DeviceInfo
├── ViewModels/ → List & Detail ViewModels, BLEManager
├── Views/ → SwiftUI UI for listing and viewing details
└── BLEAudioConnectApp → App entry point
