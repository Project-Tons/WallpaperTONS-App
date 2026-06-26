<div align="center">

  <img src="https://img.itch.zone/aW1nLzI2ODAzMjk0LnBuZw==/original/AZEzq9.png" alt="WallpaperTONS Logo" width="110">
  
  <h1 align="center">W A L L P A P E R T O N S</h1>

  <b>Desktop Environment Orchestration & Media Rendering Pipeline</b>
  <br>
  <i>The ultimate free live wallpaper engine and transparent taskbar utility for Windows.</i>

  <br><br>

  <a href="#"><img src="https://img.shields.io/badge/Platform-Windows_10%20%7C%2011-0078D4.svg?style=for-the-badge&logo=windows" alt="Platform"></a>
  <a href="#"><img src="https://img.shields.io/badge/Architecture-x64-black.svg?style=for-the-badge" alt="Architecture"></a>
  <a href="#"><img src="https://img.shields.io/badge/Rendering-WebView2_Accelerated-success.svg?style=for-the-badge" alt="Rendering"></a>
  <a href="#"><img src="https://img.shields.io/badge/Telemetry-Zero-red.svg?style=for-the-badge" alt="Telemetry"></a>

</div>

<br>

> **Overview:** WallpaperTONS is a powerful, lightweight alternative to Wallpaper Engine. It replaces standard background processes with a strictly optimized, C#/WPF native shell. It bypasses conventional web-wrapper bottlenecks to deliver zero-latency 4K/8K animated backgrounds, interactive live wallpapers, and direct Windows taskbar manipulation.

---

### Ⅰ. Key Features & Technical Capabilities

* **Advanced Taskbar Customization (DWM Shell Hooking):** Natively interfaces with the Windows Desktop Window Manager to inject Fluent Design materials into the taskbar (Acrylic, Gaussian Blur, Fully Transparent Taskbar) in real-time.
* **Hardware-Accelerated Live Wallpapers:** Offloads dynamic `project.json` and video loop decoding to the GPU via a custom WebView2 pipeline, preventing CPU overhead and ensuring smooth animated backgrounds.
* **Uncompressed Asset Delivery:** Direct indexing and deployment of raw high-resolution media without compression artifacts.
* **Algorithmic Caching:** Infinite-scrolling discovery feed built on a continuous caching architecture for zero-friction navigation and easy wallpaper discovery.
* **Air-Gapped Operation:** Fully localized repository management allowing environment deployment without active network dependencies.

---

### Ⅱ. Runtime Environment Matrix

| Specification | Minimum Threshold | Optimal Configuration |
| :--- | :--- | :--- |
| **OS Target** | Windows 10 (Build 19041+) | Windows 11 (Latest Build) |
| **Instruction Set** | x64 Architecture | x64 Architecture |
| **Memory Allocation** | 2 GB RAM | 4 GB RAM |
| **Graphics API** | DirectX 12 Compatible | Dedicated Silicon (NVIDIA / AMD) |
| **Runtime Dependency**| Edge WebView2 | Edge WebView2 |

---

### Ⅲ. Deployment Protocol (How to Install)

The application is compiled as a standalone executable. System registry modification is not required.

1. Acquire the latest `x64` binary from the **Releases** directory.
2. Initialize the application locally.
3. Modify shell parameters and set your live wallpaper via the graphical interface.

---

<div align="center">
  <h3>• Interface Architecture & Screenshots •</h3>
  <br>
  <img src="https://img.itch.zone/aW1hZ2UvNDQ5NjAxMi8yNjgwMjkzMS5wbmc=/original/7%2FWNO6.png" alt="WallpaperTONS Core Interface" width="100%">
  <br><br>
  <img src="https://img.itch.zone/aW1hZ2UvNDQ5NjAxMi8yNjgwMjkyOS5wbmc=/original/fnXRzP.png" alt="Live Wallpaper Media Discovery" width="100%">
  <br><br>
  <img src="https://img.itch.zone/aW1hZ2UvNDQ5NjAxMi8yNjgwMjkyOC5wbmc=/original/sAHSeG.png" alt="Live Engine Rendering Animated Background" width="100%">
  <br><br>
  <img src="https://img.itch.zone/aW1hZ2UvNDQ5NjAxMi8yNjgwMjkzMC5wbmc=/original/aU2mSZ.png" alt="Wallpaper Vault Management" width="100%">
  <br><br>
  <img src="https://img.itch.zone/aW1hZ2UvNDQ5NjAxMi8yNjgwMjkyNy5wbmc=/original/Q4BKtN.png" alt="Transparent Taskbar System Settings" width="100%">
</div>
