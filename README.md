# JMC Finance Tracker — Official Public Releases

Official public distribution repository for **JMC Finance Tracker** (Jagannath Computer).

This repository is public and is used strictly for distributing compiled application installers, Android APKs, update manifests, and SHA-256 checksums to user, manager, and office machines.

> **Security Guarantee**: This repository contains ONLY compiled installer executables, APKs, update metadata, and public release notes. The source repository remains private. No database files, credentials, tokens, or financial records are ever hosted here.

---

## 📥 Current Release: Version 1.1.3

- **Version**: `1.1.3` (Build 5)
- **Release Date**: 2026-11-02
- **Platforms**: Windows 10 / 11 (64-bit) & Android 8.0+

### Download Links
- **Windows Installer**: [`JMC_Finance_Tracker_Setup.exe`](https://github.com/MICHITI/jcm_finance_tracker_releases/releases/download/v1.1.3/JMC_Finance_Tracker_Setup.exe)
  - **SHA-256**: `0a9b8e1daede238c48607b9fc53782bacebc66447a382a672839782192325663`
- **Android APK**: [`jcm_finance_tracker_latest.apk`](https://github.com/MICHITI/jcm_finance_tracker_releases/releases/download/v1.1.3/jcm_finance_tracker_latest.apk)
  - **SHA-256**: `a9050542dfb633bd2d3c54eac7a936d891f8c438b30fd95e174c692e57892aa2`
- **Online Manifest**: [`update_manifest.json`](https://raw.githubusercontent.com/MICHITI/jcm_finance_tracker_releases/main/update_manifest.json)

---

### Verification (PowerShell)
You can verify the downloaded installer anytime using PowerShell:
```powershell
# Windows Installer Verification
(Get-FileHash 'JMC_Finance_Tracker_Setup.exe' -Algorithm SHA256).Hash.ToLower()
# Expected: 0a9b8e1daede238c48607b9fc53782bacebc66447a382a672839782192325663

# Android APK Verification
(Get-FileHash 'jcm_finance_tracker_latest.apk' -Algorithm SHA256).Hash.ToLower()
# Expected: a9050542dfb633bd2d3c54eac7a936d891f8c438b30fd95e174c692e57892aa2
```

---

### Release Notes (v1.1.3)
- **Direct Auto-Update**: Direct upgrade path from installed Version 1.1.1 to Version 1.1.3 on both Windows and Android without intermediate step.
- **Finance Quick Actions Redesign**: Redesigned to match Shop Management styling with colorful filled buttons, 10px rounded corners, responsive spacing, and dedicated color hierarchy.
- **Software Update for Employee & Shop Manager**: Visible in-app update checking and installation directly from Dashboard and Settings for all authenticated roles.
- **My Loans Test Data Cleanup Tool & Bulk Delete Fix**: Safe review and bulk removal of testing records (`RECON-LOAN-...`) with permanent remote cloud synchronization delete enqueuing, preventing resurrect bugs.
- **Employee Salary History & Increment Management**: Full audit tracking with non-retroactive historical monthly salary resolution based on effective dates.
- **Employee Promotion Management**: Complete designation promotion tracking linked optionally to salary increments.
