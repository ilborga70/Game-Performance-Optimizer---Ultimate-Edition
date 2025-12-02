# 🎮Game Performance Optimizer - Ultimate Edition🎮

# <img width="2572" height="1673" alt="Game Performance Optimizer - Ultimate Edition 3 0 0 0" src="https://github.com/user-attachments/assets/0a85a12a-78dd-40e7-a5de-9eef98af30c5" />

## 🚀 New Features

### 🛠️ Tab 1: SCL Gaming Boost Integration
- **Smart Launcher:** Replaced the generic "Check Status" button with **"Open SCL Gaming Boost"**.
- **Auto-Discovery:** The script now automatically scans your PC (Desktop, Downloads, Program Files, and all connected drives) to find `SCL Gaming Boost.exe`.
- **Download Prompt:** If the tool is not found, a pop-up offers to open the official GitHub release page for immediate download.

### 🧹 Tab 3: Deep Driver Cleanup
- **New "Deep Clean" Button:** Added a specific tool to prepare your PC for new GPU drivers.
- **Functionality:** Aggressively removes old installer leftovers (`C:\NVIDIA`, `C:\AMD`) and wipes the System Temp folder to prevent driver conflicts (acting as a "DDU Prep" step).

## 🔧 Improvements & Fixes

- **✅ Fixed Cache Feedback:** Resolved a bug where `Clear DirectX`, `NVIDIA`, and `AMD` cache buttons executed silently. They now correctly display a **green success message** (e.g., "DirectX Cache Cleared!") in the status bar upon completion.
- **📝 Pro Checklist Update (Tab 5):** Added advanced competitive tweaks including:
  - **HPET:** Instructions to disable High Precision Event Timer.
  - **Exploit Protection:** Guide to disabling Control Flow Guard (CFG) to fix stutter in DX12 games.
  - **ISLC:** Tips for Intelligent Standby List Cleaner.
- **🌍 Localization:** The entire interface, tooltips, and status messages have been fully translated into **English**.

## ⚙️ Technical Changes
- Refactored the `Clean-Cache` function to return valid status flags, ensuring the UI always responds to user actions.
- Improved error handling for the recursive file search to prevent freezing when scanning large drives.

## 🏁 Overview

Game Performance Optimizer is a comprehensive **portable Windows application** designed to maximize gaming performance through systematic optimization of Windows settings, hardware resources, and game-specific configurations. 

Distributed as a standalone script/executable, this tool requires no installation and leaves no traces on your system. Unlike generic "boosters," this utility provides professional-grade optimizations based on competitive gaming principles and **Unreal Engine 5** specific performance characteristics.

## ⚙️ Key Features

### **Portable, Clean & Adaptive**
- **Zero Installation**: Run directly from any location (USB, Desktop).
- **Self-Contained**: No external assets required (Icons and code are embedded).
- **Adaptive UI**: Toggle instantly between **Dark Mode** (Gamer/Cyberpunk) and **Light Mode** (Office).

### **1. Disk & Indexing Management**
- **Smart Indexing Control**: Exclude game directories from Windows Search indexing to reduce disk I/O contention.
- **Status Monitoring**: Real-time checking of current indexing status for selected games.
- **History Tracking**: Maintain optimization history with quick-load functionality.

### **2. CPU, Priority & Compatibility (NEW)**
- **Dual-Write Registry Technology**: Applies compatibility flags to both **Current User (HKCU)** and **Local Machine (HKLM)** hives. This ensures settings like "Run as Admin" stick permanently, bypassing Windows overrides.
- **Permanent Admin Flag**: Force games to *always* run as Administrator without right-clicking.
- **High DPI Scaling Override**: Disable high DPI scaling behavior to fix mouse "floatiness" and cursor misalignment in older or UE5 titles.
- **Fullscreen Optimizations (FSO)**: Disable Windows FSO to eliminate input lag and micro-stutters.
- **One-Click Launch**: Button to immediately launch the selected game with elevated privileges.
- **Unified Status Check**: A single report summarizing CPU Priority, FSO status, DPI scaling, and Admin rights.

### **3. Cache & Power Management**
- **Shader Cache Cleaner**: Clear **DirectX**, **NVIDIA**, and **AMD** caches. Crucial for fixing **Unreal Engine 5 stuttering** (compilation lag).
- **Power Plan Control**: Force High Performance mode to prevent CPU frequency drops/parking during gameplay.

### **4. Network & Latency Tweaks**
- **Registry Optimizations**: Disable *Network Throttling Index* and set *System Responsiveness* to 0 for competitive gaming.
- **TCP Optimization**: Tuned for lowest packet latency.
- **Safe Reversion**: Restore Windows network defaults with a single click.

### **5. Professional Competitive Checklist**
- **Comprehensive Guide**: BIOS settings (XMP, Resizable BAR), Monitor config, and Input optimization.
- **UE5-Specific Fixes**: Step-by-step guide for `Engine.ini` tweaks (`r.TextureStreaming`, `r.CreateShadersOnLoad`).
- **Maintenance Routine**: Weekly and monthly optimization schedules.

---

## 🚀 Portable Usage

### **System Requirements**
- Windows 10/11 (64-bit)
- .NET Framework 4.8 (Standard on most modern Windows PCs)
- **Administrator privileges required for full functionality**

### **Running the Application**
1. **Download** the script/executable.
2. **Place anywhere** - desktop, game folder, or USB drive.
3. **Run as Administrator**: Right-click and select "Run as Administrator" (Critical for HKLM Registry writes).
4. The GUI loads automatically with the embedded high-quality icon.

### **⚠️ Security Note**
Since this is a community-developed tool, Windows SmartScreen may show a warning:
- Click **"More info"** → **"Run anyway"**.
- The application is completely safe, open-source (PowerShell based), and only modifies standard Windows gaming keys.

---

## 🛠️ Optimization Guide

### **Quick Start (The "Anti-Stutter" Setup)**
1. **Launch** the tool as Administrator.
2. **Tab 1**: Select your game `.exe` → Click **"Exclude Indexing"**.
3. **Tab 2**: 
   - Click **"Set High Priority"**.
   - Click **"Disable FSO"** (Fixes input lag).
   - Click **"Disable High DPI Scaling"** (Fixes mouse feel).
   - Click **"Force Admin (Always)"** (Ensures permissions).
4. **Tab 3**: Click **"Clear DirectX Cache"** + **"Force High Performance"**.
5. **Tab 4**: Click **"Apply Network Optimizations"** (Restart required).

### **UE5 Specific Fix (Engine.ini)**
Refer to **Tab 5 (Pro Checklist)** for the critical `Engine.ini` edits that solve shader compilation stuttering in Unreal Engine 5 games.

---

## 💾 Settings & History

- **Smart History**: Remembers the last 10 games you optimized for both Indexing and CPU/Compatibility settings.
- **Load Selected**: Quickly re-apply settings to a previously optimized game from the list.
- **Dual-Layer Safety**: Optimizations are applied using robust methods that check both user and system-wide registry keys to ensure they apply correctly to protected folders (like `Program Files`).

---

## 🎯 Competitive Gaming Focus

This tool is built specifically to address modern gaming issues:

- **UE5 Stutter Fix**: Aggressive shader cache cleaning and priority management.
- **Input Lag Reduction**: Disabling FSO and High DPI scaling restores raw mouse input.
- **Network Stability**: Registry tweaks used by competitive esports players.
- **Portability**: Carry your optimization toolkit on a USB drive to LAN parties or tournaments.

---

> **Note**: This is a powerful tool that modifies system registry keys. While all changes are designed to be reversible via the "Restore/Reset" buttons in the app, always ensure you know what you are modifying.
