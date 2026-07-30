<div align="center">
  <img src="placeholder_logo.png" alt="uDesk Logo" width="120">
  
  <h1>uDesk Server</h1>
  
  <p><b>A local network bridge connecting your Windows PC and Android device for advanced remote control, system monitoring, and custom macro execution.</b></p>
  <p><i>Developed by UGZ Apps</i></p>

  <br>

  <a href="PLAY_STORE_LINK_HERE">
    <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" alt="Get it on Google Play" height="60">
  </a>
  &nbsp;&nbsp;
  <a href="GITHUB_RELEASE_LINK_HERE">
    <img src="https://img.shields.io/badge/Download-Latest_Release-blue?style=for-the-badge&logo=windows&logoColor=white" alt="Download for Windows" height="60">
  </a>
</div>

<br>

---

## About the Project

[cite_start]uDesk is a comprehensive desktop server application built with Python and PyQt5[cite: 1, 2]. It operates over your local network to establish a seamless connection between your Android device and Windows PC. [cite_start]Designed with a modern, dark-themed UI[cite: 212, 213], it provides a centralized dashboard for hardware monitoring, bidirectional input control, and highly customizable macro management.

<div align="center">
  <img src="placeholder_main_dashboard.png" alt="uDesk Main Dashboard" width="750">
  <br>
  <i>Main server dashboard displaying active network status and configuration.</i>
</div>

---

## Features

### Bidirectional Input Control
uDesk provides a unique two-way interaction model for mouse and keyboard inputs:
* **Android to PC (Touchpad):** Use your Android device as a low-latency wireless touchpad. [cite_start]Movement and click data are transmitted directly to the PC via a dedicated UDP server[cite: 58, 60].
* [cite_start]**PC to Android (Input Forwarding):** Press a configured hotkey on your PC to lock the system cursor (centering and hiding it)[cite: 17, 51]. [cite_start]All subsequent physical mouse movements and keyboard strokes are captured and forwarded directly to the Android device for remote typing and navigation[cite: 42, 46].

<div align="center">
  <img src="placeholder_input_mode.png" alt="Input Control Modes" width="750">
  <br>
  <i>Demonstration of the input forwarding state.</i>
</div>

### JSON-Based Mod Editor (Macro Deck)
[cite_start]Create custom control decks for your Android device using the built-in Mod Editor[cite: 273].
* [cite_start]**Custom Actions:** Assign commands such as system power states, complex keyboard shortcuts, file/folder execution, or audio playback[cite: 280, 281, 282, 283, 284].
* [cite_start]**Icon Integration:** Search and assign vector icons directly from the integrated Lucide SVG repository[cite: 303, 308].
* [cite_start]**Visual Layout:** Reorder, edit, and manage your buttons in a clean interface, saving configurations as JSON files that sync instantly with the mobile app[cite: 348, 349].

<div align="center">
  <img src="placeholder_mod_editor.png" alt="Mod Editor Interface" width="750">
  <br>
  <i>The built-in editor for creating custom macros and button layouts.</i>
</div>

### Application & Media Management
* [cite_start]**App Launcher:** Add `.exe` executables or `.lnk` shortcuts to the PC dashboard[cite: 190, 200]. [cite_start]These appear on your Android device for one-tap remote launching[cite: 112, 114].
* [cite_start]**Advanced Audio Mixer:** Not just a master volume slider. uDesk fetches active Windows audio sessions, allowing you to mute or adjust the volume of individual background applications directly from your phone[cite: 124, 129].

<div align="center">
  <img src="placeholder_app_launcher.png" alt="App Launcher and Mixer" width="750">
  <br>
  <i>Managing remote applications and per-app audio levels.</i>
</div>

### Dashboard Customization & Sync
* [cite_start]**Android Wallpaper Setup:** Browse and select a local image on your PC; uDesk encodes it and sets it as the background for your Android application to maintain your aesthetic[cite: 173, 189].
* [cite_start]**Media / URL Preview:** Paste an image or GIF URL into the PC server to display it as a custom widget on your Android dashboard[cite: 171, 185].
* [cite_start]**Live Media Sync:** Automatically fetches the currently playing media title, artist, and album art via Windows APIs and pushes it to the mobile interface[cite: 11, 14].

### Utilities & Productivity
* [cite_start]**Screen Capture Snipping:** Use the built-in frameless snipping tool to capture a specific area of your PC screen[cite: 154]. [cite_start]The captured image is immediately sent and displayed on your Android device[cite: 158].
* [cite_start]**System Monitoring:** Streams real-time CPU usage, RAM allocation, and Network bandwidth (Mbps) to the connected mobile client[cite: 78, 80].
* [cite_start]**Clipboard Synchronization:** Automatically detects changes in your PC's clipboard and pushes them to Android, while also accepting clipboard data pasted from the mobile app[cite: 93, 132].

<div align="center">
  <img src="placeholder_snipping_tool.png" alt="Snipping Tool" width="750">
  <br>
  <i>Capturing a custom screen region to send to the mobile device.</i>
</div>

---

## Setup and Connection

1. **Run the Server:** Launch the `uDesk` executable on your Windows machine. The application runs locally and generates a secure environment.
2. **Network Requirements:** Ensure both your PC and Android device are connected to the same local area network (LAN/Wi-Fi).
3. **Pairing:**
   * [cite_start]The PC dashboard will display your automatically detected **Server IP** and a randomly generated **Security Token**[cite: 175, 176].
   * Open the uDesk Android app, enter these credentials, and tap connect.

<div align="center">
  <img src="placeholder_pairing.png" alt="Pairing Process" width="750">
  <br>
  <i>The automated IP and Security Token generation.</i>
</div>
