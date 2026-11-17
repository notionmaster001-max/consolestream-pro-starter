# 🎮 ConsoleStream Pro Starter (Audio Sync Calibrator)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](README.md)
[![Full Toolkit](https://img.shields.io/badge/Full_Toolkit-$19.99-ff2a85.svg)](https://notionmaster001.gumroad.com/l/aqvsyl)

A precision hardware-clock calibration tool designed to measure and eliminate audio/video desync when streaming console games (PS5, Xbox Series X) via capture cards in OBS Studio.

---

## ⚡ What's in this Free Starter Edition

- **Interactive Metronome (`audio-sync-tester.html`):**
  - High-precision 60 BPM and 120 BPM dual-mode metronome powered by the Web Audio API hardware clock.
  - Synchronized high-contrast visual flash + 1,000Hz calibration sine beep.
  - Built-in Frame Delay Calculator for 30 FPS and 60 FPS video streams.

---

## 🚀 Upgrade to Full ConsoleStream Pro Toolkit ($19.99)

Fix both audio desync AND washed-out console HDR graphics:

| Feature | Free Starter | [Full Commercial Toolkit ($19.99)](https://notionmaster001.gumroad.com/l/aqvsyl) |
|:---|:---:|:---:|
| **Sync Metronome** | ✅ Included | **✅ Dual-Mode Hardware Clock Metronome** |
| **Frame Delay Calculator** | ✅ Included | **✅ Interactive Millisecond Calculator** |
| **4-Parameter HDR Color Preset** | ❌ None | **Instant Fix for Washed-Out Foggy Console SDR Capture** |
| **Hardware Latency Benchmarks** | Basic | **Certified Offsets for Elgato HD60X, 4K Pro & AVerMedia** |
| **Optimization Manual** | Basic | **Comprehensive Capture Card Optimization Manual** |

👉 **[Unlock Full Console Calibration Toolkit & HDR Fix ($19.99)](https://notionmaster001.gumroad.com/l/aqvsyl)**

---

## ⏱️ Quick Calibration Steps

1. Open `audio-sync-tester.html` in your browser.
2. Record a 10-second test video in OBS showing the flashing metronome with your capture card game audio unmuted.
3. Play back in VLC (press `E` to step frame-by-frame). Count frames between the neon flash and audio beep.
4. Open OBS → Edit → **Advanced Audio Properties** → Set **Sync Offset (ms)** for your capture card audio.

---

## 📄 License

MIT License. See [LICENSE](LICENSE) for details.
