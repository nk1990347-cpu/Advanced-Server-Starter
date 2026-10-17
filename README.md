# 🚀 Advanced Server Starter (V2.0.0)

A lightweight, high-performance desktop utility designed for developers to instantly spin up local servers with **live-reload capabilities** and **zero-install secure global public tunneling** via `localhost.run`.

* **Release Page**: [GitHub Releases - V2.0.0](https://github.com/nk1990347-cpu/Advanced-Server-Starter/releases/tag/V2.0.0)[cite: 3]
* **Direct Executable Download**: [AE-Apps_Advanced_Server_Starter.exe](https://github.com/nk1990347-cpu/Advanced-Server-Starter/releases/download/V2.0.0/AE-Apps_Advanced_Server_Starter.exe)[cite: 3]

---

## 📊 Overview: Benefits, Features & VS Code Comparison

| Category | Advanced Server Starter (V2.0.0) | VS Code (Live Server / Port Forwarding) |
| :--- | :--- | :--- |
| **Primary Focus & Benefits** | Instant lightweight file/folder serving, zero bloat, and fast global sharing | Heavy IDE environment with code editing & extensions |
| **Startup Speed** | Instantaneous standalone tray/desktop widget | Requires opening a heavy editor workspace first |
| **Global Tunneling** | Built-in zero-config `localhost.run` SSH public tunnels | Requires Microsoft/GitHub account login or CLI extensions |
| **Multi-Server Support** | Run and manage multiple independent server paths concurrently | Limited to single active workspace server instances |
| **Live Reload** | Built-in real-time DOM injection event-source listener | Relies on third-party extension overheads |
| **Custom Shortcuts** | Global background hotkeys (`ctrl+alt+h`, `ctrl+alt+f`, etc.) | Limited to IDE shortcut bindings |

---

## ✨ Key Features

* **Dual Local & Global Modes**: Spin up quick local environment servers (`127.0.0.1`) or broadcast live public links (`.lhr.life`) instantly.
* **Smart Space Encoding**: Fully handles filenames containing spaces (e.g., `index 3.html` $\rightarrow$ `index%203.html`) to completely eliminate 404 Not Found errors.
* **Active Servers Manager**: Track, rename (with persistent `(Global)` tagging), open in browser, or terminate running instances through an interactive system popup menu.
* **Customizable Hotkeys & Themes**: Tailor your workflow with fully remappable global keyboard shortcuts and dynamic theme/GIF background persistence.
* **Standalone Executable Friendly**: Bundled with robust runtime error handling and clean logging profiles under `LocalAppData\AE_Apps`.

---

## 🛠️ Used Technologies

* **Python 3.11+**: Core system logic and concurrency management.
* **Tkinter & Custom DWM**: Native borderless window styling, dark mode layouts, and smooth drop shadows for Windows.
* **Pillow (PIL)**: High-performance image rendering and animated GIF background processing.
* **Subprocess & OpenSSH**: Secure, zero-config public TCP/TLS tunneling via `localhost.run`.
* **Keyboard Module**: Global low-level background hotkey hook registration.

---

## 📖 How To Use

1. **Download & Run**: Grab the executable from the [Release Link](https://github.com/nk1990347-cpu/Advanced-Server-Starter/releases/download/V2.0.0/AE-Apps_Advanced_Server_Starter.exe)[cite: 3] or run your script directly.
2. **Start a Local Server**: Click the main **Start Server** button or use the shortcuts (`Ctrl + Alt + H` / `Ctrl + Alt + F`) to choose a file or folder path.
3. **Launch a Global Tunnel**: Access the settings gear (`⚙️`) $\rightarrow$ **Global Start New Server** to generate a live public `.lhr.life` URL shareable anywhere.
4. **Manage Instances**: Click the live status text area (`✅ Running...`) to open the **Active Servers Manager** popup where you can rename, check ports, or terminate sessions.
5. **Configure Hotkeys**: Open the settings menu $\rightarrow$ **Edit Shortcut** to customize both your Local and Global keybindings seamlessly.
