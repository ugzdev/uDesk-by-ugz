<div align="center">
  <h1>uDesk PC Server</h1>
  <p><b>The official desktop companion for the uDesk remote management ecosystem.</b></p>
  <p>
    <a href="README-tr.md">Türkçe Dokümantasyon</a>
  </p>
</div>

---

## Overview

uDesk is a comprehensive remote computer management and launcher system. While the mobile application serves as your primary control center, this repository hosts the PC-side server application. It operates silently in the background, bridging the connection between your mobile device and your desktop environment to execute commands, manage tasks, and monitor system performance securely.

## Core Features

### PC Companion App (This Repository)
* **Seamless Connectivity:** Establishes a secure, low-latency connection with the mobile client over your local network.
* **Minimal Footprint:** Designed to run in the background with near-zero impact on system resources.
* **Process & Task Management:** Grants the ability to remotely monitor active processes, terminate tasks, and launch applications.
* **System Controls:** Enables remote power management including shutdown, restart, and sleep commands.

### Mobile Application (Available on Google Play)
* **Intuitive Interface:** A clean, modern launcher design providing quick access to PC controls and shortcuts.
* **Real-time Telemetry:** View live PC hardware statistics and performance metrics directly from your phone.
* **Custom Shortcuts:** Pin frequent actions and custom scripts for one-tap execution.

## Downloads & Installation

To experience the full ecosystem, you need to install both the desktop server and the mobile application.

### 1. Mobile Client (Android)
Download the remote control and launcher application directly from the Google Play Store.

**Download:** [uDesk on Google Play](https://play.google.com/store/apps/details?id=com.ugz.udesk)

### 2. Desktop Server (Windows/Linux)
Download the latest executable for your computer to start receiving commands from your mobile device.

**Download:** [Latest PC Server Release](https://github.com/UGZ/uDesk/releases/latest)

## Setup Guide

1. Download the latest `.zip` or `.exe` file from the Releases page.
2. Extract the contents to your preferred directory.
3. Run the PC Server application.
4. Note the IP address and Port displayed on the application window.
5. Ensure your operating system's firewall allows the application to communicate over the network.
6. Open the uDesk Android application, navigate to the connection settings, and enter the displayed IP and Port.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

<div align="center">
  <b>Developed by UGZ Apps</b>
</div>
