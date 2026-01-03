# ghost-trace
PowerShell system maintenance suite
# GHOST_TRACE 🛠️

**GHOST_TRACE v3.1** is a PowerShell-based system maintenance and optimization suite
designed for modern Intel-based Windows systems, with special tuning for Lenovo hardware.

Built to be safe, reversible, and low-noise.

## Features
- System restore point creation
- Deep junk and cache cleanup (Intel Arc aware)
- Privacy trace removal
- Startup optimization
- Driver updates via Windows Update
- Software updates via winget
- SFC & DISM integrity scans
- Hardware snapshot summary

## Requirements
- Windows 11
- PowerShell 7+ recommended
- Administrator privileges
- winget installed

## Usage
```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
.\GhostTrace.ps1
