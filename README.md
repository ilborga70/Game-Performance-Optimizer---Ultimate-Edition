# <img width="2613" height="1690" alt="Game Performance Optimizer - Ultimate Edition 1 0 0 0" src="https://github.com/user-attachments/assets/4cd9b037-598f-4b79-9257-92e59fca5a7d" />

A powerful, all-in-one executable tool designed to enhance gaming performance, fix stuttering (especially in Unreal Engine 5 games), and reduce input latency by applying competitive Windows and system tweaks.

This tool is distributed as a **portable .exe** and requires **Administrator privileges** to function correctly.

⚠️ **Note on Download:**  
Some web browsers or antivirus software may show **false positive warnings** when downloading or running portable `.exe` files. This happens because the tool applies advanced system tweaks and registry changes. The executable is safe to use, but you should always download it from the official repository to ensure authenticity.

---

## ✨ Features Overview

The optimizer is organized into five main tabs, plus a suite of advanced system tweaks.

---

## 1️⃣ Disk & PC Check

This tab focuses on disk indexing and launching the companion "Gaming PC Check" tool.

| Feature | Description |
| :--- | :--- |
| **Indexing Management** | Select a game's folder to **Exclude Indexing** (recommended for game folders on any drive) or **Re-enable Indexing** to restore defaults. |
| **Optimization History** | Tracks a history of game folders whose indexing status has been modified. |
| **Gaming PC Check** | A dedicated section to **Launch** or **Download** a separate, external tool called "Gaming PC Check" (SCL) for in-depth system analysis. |

---

## 2️⃣ CPU & Priority Manager

This section manages per-game CPU priority, compatibility flags, and GPU settings for high-performance execution.

| Feature | Description |
| :--- | :--- |
| **Game Selection** | Allows browsing for a target game's `.exe` file. |
| **CPU Priority** | Permanently sets the game's **CPU Priority** to **High** or restores it to **Normal** via Windows Registry settings. |
| **Launch as Admin** | Option to launch the selected game with administrative rights for a single session. |
| **Compatibility Flags** | Toggles key Windows compatibility settings: |
| | - **Disable/Restore FSO** (Fullscreen Optimization, often fixes stuttering). |
| | - **Disable/Restore High DPI Scaling Override**. |
| | - **Force/Remove Permanent Admin Flag** (Runs the game as Administrator every time). |
| **GPU Preference** | For any selected desktop app, you can **Add/Update GPU High Perf.** to force it to use the dedicated high-performance GPU. |
| **Full Status Check** | A button to display the current state of all priority, compatibility, and GPU preference settings for the selected executable. |

---

## 3️⃣ Cache & Power Management

Tools for cleaning system cache and managing power delivery to the CPU.

| Feature | Description |
| :--- | :--- |
| **Shader Cache Cleaner** | Clears cached shaders (often a primary fix for stuttering in games like those built on Unreal Engine 5). |
| | - **Clear DirectX Cache**. |
| | - **Clear NVIDIA Cache**. |
| | - **Clear AMD Cache**. |
| **Deep Driver Cleanup** | An aggressive cleanup tool to prepare your system before installing new GPU drivers. |
| **Power Plan** | **Force High Performance** or **Set Balanced** to prevent the CPU from downclocking under gaming load (critical for performance consistency). |

---

## 4️⃣ Network & Latency

Registry tweaks to reduce competitive network latency. **(Restart Required)**

| Feature | Description |
| :--- | :--- |
| **Apply Network Optimizations** | Tweaks the Windows Registry to **disable Network Throttling** and set **SystemResponsiveness to 0** (optimizing for gaming performance over background tasks). |
| **Reset Windows Defaults** | Restores the default values for all network registry tweaks. |

---

## 5️⃣ Pro Checklist

A read-only text area containing advanced, manual tips for competitive gamers.

* **UE5 Optimization:** Manual configuration file edits (`Engine.ini`) to force shader compilation and prevent texture streaming issues.
* **Hardware/BIOS:** Tips on enabling **XMP/DOCP** for RAM speed, **Resizable BAR**, and **disabling HPET** for lowest input latency.
* **Windows & In-Game:** Reminders for enabling Game Mode, checking refresh rates, disabling mouse acceleration, and managing background apps.

---

## ⚙️ Advanced System Tweaks (Toggles)

The tool includes underlying logic to manage several advanced system-wide settings using simple on/off toggles:

| Category | Optimization Toggle | Goal |
| :--- | :--- | :--- |
| **Latency/System** | **Disable HPET** | Lowers input latency by disabling the High Precision Event Timer. |
| | **Dynamic Tick** | Disables Dynamic Tick for potentially better performance stability. |
| | **Nagle's Algorithm** | Disables this TCP optimization for lower ping/latency in online games. |
| **Memory** | **ISLC (Intelligent Standby List Cleaner)** | Manages the Windows standby list to prevent memory-related stutter. |
| | **Large Pages** | Enables the use of large memory pages for better RAM allocation. |
| | **Disable RAM Compression** | Disables Windows memory compression features. |
| **Storage** | **SSD Optimizations** | Applies recommended tweaks for Solid State Drives (e.g., disables prefetcher, ensures TRIM is active). |
| | **Clear Pagefile at Shutdown** | Forces the system to clean the pagefile on shutdown for security and resource management. |
| **GPU/Video** | **HAGS/GPUScheduler** | Tweaks for Hardware-accelerated GPU Scheduling. |
| | **NVIDIA Reflex / Low Latency Mode** | Manages NVIDIA's built-in latency-reducing features. |
| **Windows Services** | **Disable Game DVR/Xbox Services** | Deactivates non-essential services that can consume resources. |
| | **Disable Cortana/Search** | Disables the Cortana assistant and related search features. |

---

## ⚠️ Important Note

* **Administrator Privileges:** This tool requires running as an **Administrator** to apply most system and registry tweaks.  
* **System Restart:** Certain advanced optimizations (like Network Tweaks and HPET) require a **system restart** to take full effect.  
* **Browser Warnings:** If your browser flags the download as unsafe, it is a **false positive** due to the nature of portable `.exe` files. Always verify that you are downloading from the official repository.

---

## ❓ FAQ (Frequently Asked Questions)

**Q1: Why does my browser/antivirus warn me when I download the file?**  
A: Portable `.exe` files that apply system tweaks can trigger **false positives**. This is normal behavior. The tool is safe if downloaded from the official repository.

**Q2: Do I need to install the program?**  
A: No. The tool is **portable** — just run the `.exe` file. No installation is required.

**Q3: Why are Administrator privileges required?**  
A: Because the optimizer modifies **Windows Registry settings** and system configurations that affect performance. Without admin rights, these tweaks cannot be applied.

**Q4: Will this tool harm my system?**  
A: No. All tweaks are **reversible** and can be reset to Windows defaults. The tool is designed to optimize performance without compromising stability.

**Q5: Do I need to restart my PC after applying tweaks?**  
A: Yes, for certain optimizations (like **Network Tweaks** and **HPET disable**) a restart is required to take full effect.

**Q6: Can I use this tool on any version of Windows?**  
A: It is optimized for **Windows 10 and Windows 11**. Some features may not be available on older versions.

