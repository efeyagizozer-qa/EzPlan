# EzPlan 🎯

A lightweight, zero-dependency, iOS-optimized Progressive Web App (PWA) built for tracking weekly academic schedules, coursework deadlines, and exam preparation.

**Live App:** [https://efeyagizozer-qa.github.io/EzPlan/](https://efeyagizozer-qa.github.io/EzPlan/)

## ✨ Features

* **iOS Home Screen Ready:** Runs in standalone full-screen mode on iPhone with native `-apple-system` (SF Pro) typography and OLED dark theme.
* **Dual-Layer State Persistence:** Automatically saves task progress to `localStorage` and encodes state into the URL hash (`#s=`) so progress persists across sessions.
* **Day-by-Day Filtering & Live Progress:** Filter tasks by day, add custom tasks on the fly, and monitor overall completion with an animated progress ring.
* **iPhone Lock Screen Widget Generator:** Generates a custom 1179×2556 wallpaper card aligned beneath the iOS Lock Screen clock showing upcoming tasks.
* **Zero External Dependencies:** Single-file HTML/CSS/JS architecture for instant offline-capable loading.

## 📱 iPhone Setup

1. Open [EzPlan](https://efeyagizozer-qa.github.io/EzPlan/) in **Safari** on iPhone.
2. Tap the **Share** button and select **Add to Home Screen**.
3. *(Optional)* Create an Apple **Shortcut** using **Open URLs** pointing to the live link to add a 2-slot widget directly under your Lock Screen clock.
