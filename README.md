# JMC Finance Tracker — Official Public Releases

Official public distribution repository for **JMC Finance Tracker** (Jagannath Computer).

This repository is public and is used strictly for distributing compiled application installers, Android APKs, update manifests, and SHA-256 checksums to user, manager, and office machines.

> **Security Guarantee**: This repository contains ONLY compiled installer executables, APKs, update metadata, and public release notes. The source repository remains private. No database files, credentials, tokens, or financial records are ever hosted here.

---

## 📥 Current Release: Version 1.1.5

- **Version**: `1.1.5` (Build 7)
- **Release Date**: 2026-11-02
- **Platforms**: Windows 10 / 11 (64-bit) & Android 8.0+

### Download Links
- **Windows Installer**: [`JMC_Finance_Tracker_Setup.exe`](https://github.com/MICHITI/jcm_finance_tracker_releases/releases/download/v1.1.5/JMC_Finance_Tracker_Setup.exe)
- **Android APK**: [`jcm_finance_tracker_latest.apk`](https://github.com/MICHITI/jcm_finance_tracker_releases/releases/download/v1.1.5/jcm_finance_tracker_latest.apk)
- **Online Manifest**: [`update_manifest.json`](https://raw.githubusercontent.com/MICHITI/jcm_finance_tracker_releases/main/update_manifest.json)

---

### Verification (PowerShell)
You can verify the downloaded installer anytime using PowerShell:
```powershell
# Windows Installer Verification
(Get-FileHash 'JMC_Finance_Tracker_Setup.exe' -Algorithm SHA256).Hash.ToLower()

# Android APK Verification
(Get-FileHash 'jcm_finance_tracker_latest.apk' -Algorithm SHA256).Hash.ToLower()
```

---

### Highlights (v1.1.5)
- **Fully Automatic Public Release System**: Automated GitHub Actions CI/CD pipeline for building, verifying, checksumming, and public release distribution.
- **Top Application Header Redesign**: Clean circular profile image button with role-specific indicators (Admin, Shop Manager, Staff).
- **Admin Profile Photo Support**: Offline persistent photo cropping and display.
- **Jagannath Computer Shop Branding**: Store branding on the Shop Management dashboard.
- **Adaptive Responsive UI**: Screen adaptation across mobile devices (320px–480px), tablets, and Windows Desktop.
- **Offline Data Safety**: 100% offline-first architecture; all SQLite database tables, chit funds, loans, transactions, customer credit, attendance, and employee data remain fully preserved.
