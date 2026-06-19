# Setup Issues & Fixes

This file contains recurring technical issues encountered during development setup and their troubleshooting steps.

---

## Arduino IDE Startup Issue (2.x series)

### Problem
Arduino IDE fails to launch properly and gets stuck on loading screen.

### Symptoms
- Application does not fully open
- Stuck on splash/loading screen
- No error message displayed

### Possible Causes
- Corrupted configuration or cache (Arduino15 directory)
- Unstable IDE version (2.3.x builds)
- Conflicts from previous installations
- User directory path issues (spaces or special characters)

### Attempted Fixes
- Full reinstall of Arduino IDE
- Removal of configuration folders
- Testing portable version
- Changing installation path
- Reinstalling ESP32 board packages

### Current Status
Not fully resolved. Migration to Arduino IDE 1.8.19 planned.

---

## ESP32 Board Installation Notes

### Dependency
Requires stable Arduino IDE environment.

### Common Issues
- Slow or failed board downloads
- Interruptions due to network restrictions
- Version compatibility issues with IDE 2.x

### Recommendation
Use stable IDE version before configuring ESP32 toolchain.
