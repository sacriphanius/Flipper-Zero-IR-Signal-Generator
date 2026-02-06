# IR Signal Generator & Analyzer

A powerful, visually refined Infrared Signal Generator and Analyzer application for the Flipper Zero. Designed with a high-tech aesthetic and smooth animations.

<p align="center">
  <img src="preview_1.png" width="45%" />
  <img src="preview_2.png" width="45%" />
</p>

## ✨ Features

### 📡 Signal Generator (TX)
*   **Variable Frequency:** Generates IR signals with precise frequency control from **30kHz to 60kHz**.
*   **Dynamic Animation:** Features a "Crazy Mode" spectrum animation that reacts violently during transmission, visualizing the signal output.
*   **External Module Support:** Automatically detects and switches to 5V external IR modules (pin PA7) for high-power transmission.
*   **Smart LED Feedback:** RGB LED indicates frequency range (Red: <35k, Green: <42k, Blue: <50k).

### 🔍 Signal Searcher (RX)
*   **Spectrum Analyzer:** A smooth, sine-wave based spectrum animation scans for signals ("Calm Mode") and reacts dyamically when a signal is detected ("Excited Mode").
*   **Frequency Detection:** Decodes incoming IR signals and displays the detected protocol frequency in real-time.
*   **Auto-Sync:** Automatically captures the detected RX frequency and applies it to the Generator, allowing for immediate re-transmission.

## 🎮 Controls

| Button | Action |
| :--- | :--- |
| **Left / Right** | Decrease / Increase Frequency (1kHz steps) |
| **OK** | Start / Stop Transmission (TX Mode) |
| **Long Press UP** | Switch to **Signal Searcher (RX)** Mode |
| **UP** | Return to **Generator (TX)** Mode |
| **Back** | Exit Application |

## 🎨 Visuals
*   **High-Tech UI:** Custom frames, bottom status bands, and clean typography.
*   **Reactive Animations:** The interface feels alive with wave animations that respond to the device's state (Idle, Scanning, Transmitting, Receiving).
