# Windows Multi-Sidebar

A lightweight, customizable desktop utility for Windows designed to streamline productivity by docking essential widgets, quick links, calendars, and digital clocks directly onto your desktop workspace.

---

## 🌟 Key Features

- **Multi-Panel Docking**: Anchor persistent productivity sidebars to the edge of your screen.
- **Integrated Widgets**: Built-in analog and digital clocks, calendars, and scratchpad notes.
- **Quick Links Hub**: One-click launch access to essential tools (Gmail, Calendar, Drive, AI assistants, and custom web apps).
- **Lightweight Footprint**: Optimized background performance with low CPU and memory utilization.
- **Modern Windows Integration**: Compatible with Windows 10 and Windows 11 desktop environments.

---

## 🚀 Installation & Distribution

### Direct Download (.exe / .msix)
1. Download the latest installer from the [Releases](https://github.com/sam720785/Sidebar/releases) tab.
2. Run the installer package:
   - For `.exe`: Launch the standalone installer and follow the on-screen prompts.
   - For `.msix`: Double-click the signed package and click **Install**.

---

## 🛠️ Development & Building

### Prerequisites
- Windows 10/11 (64-bit recommended)
- Python 3.10+ / Electron / C# runtime (depending on your build environment)
- MSIX Packaging Tool (for building Store packages)

### Packaging for Distribution
1. Build the standalone executable:
   ```bash
   pyinstaller --noconsole --onefile Sidebar.py
