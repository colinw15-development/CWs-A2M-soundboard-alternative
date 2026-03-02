# CWs Audio to Mic (A2M) - Soundboard Alternative

A cross-platform audio routing application that lets you upload audio files and play them directly through your microphone using virtual audio cables.

## 📋 Features

- **Soundboard** - Upload and trigger audio files (up to 15 seconds each) with custom hotkeys
- **Audio Tester** - Test different audio frequencies through your microphone
- **Multi-platform Support** - Works on macOS (Intel & Apple Silicon) and Windows (7, 8, 8.1, 10, 11)
- **Custom Hotkeys** - Assign keyboard shortcuts to trigger sounds
- **Simple Interface** - Easy-to-use navigation with sidebar menu
- **Help Guide** - Built-in setup instructions

## 🛠 Prerequisites

### macOS
- **BlackHole 2ch** - Free virtual audio cable for macOS
  - Download: https://existential.audio/blackhole/

### Windows
- **VB-Cable** - Free virtual audio cable for Windows
  - Download: https://vb-audio.com/Cable/

## 🚀 Installation

### macOS
1. Download `CW.Audio.to.Mic.0.0.2.zip` from the [Releases](../../releases) page
2. Extract the zip file
3. Open the `.app` file
4. Follow the in-app Help guide to set up BlackHole 2ch

### Windows
1. Download `CW.Audio.to.Mic.Setup.0.0.2.exe` from the [Releases](../../releases) page
2. Run the installer
3. Follow the in-app Help guide to set up VB-Cable

## 📖 Usage

1. **Setup Output Device** - Configure which virtual audio cable to use in Home settings
2. **Add Sounds** - Go to Soundboard and upload your audio files
3. **Assign Hotkeys** - Set keyboard shortcuts for each sound in the Hotkeys menu
4. **Test** - Use the Audio Tester to verify your audio is routing correctly
5. **Play** - Press your assigned hotkeys to play sounds through your mic!

## 💬 Code Review & Feedback

This project is shared for **review and feedback purposes only**. See [LICENSE](LICENSE) for usage restrictions.

### Review the Code
- **renderer.js** - Main application logic (included in this repository)

Please report bugs and send feedback to help improve this project!

## 📄 License

This project is provided under a **Restricted License**. See the [LICENSE](LICENSE) file for complete details.

**TL;DR:**
- ✅ Review, test, and provide feedback
- ❌ No redistribution, modification, or commercial use without explicit permission

---

Built with **Electron + npm**

Questions or feedback? Open an issue!