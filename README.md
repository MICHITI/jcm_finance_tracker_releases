# JMC Finance Tracker — Official Public Releases

Official public distribution repository for **JMC Finance Tracker** (Jagannath Computer).

This repository is public and is used strictly for distributing compiled application installers, update manifests, and SHA-256 checksums to customer and office Windows machines.

> **Security Guarantee**: This repository contains ONLY compiled installer executables, update metadata, and public release notes. The source repository remains private. No database files, credentials, tokens, or financial records are ever hosted here.

---

## 📥 Current Release: Version 1.1.0

- **Version**: `1.1.0`
- **Release Date**: 2026-11-01
- **Platform**: Windows 10 / 11 (64-bit)
- **Installer File**: [`JMC_Finance_Tracker_Setup.exe`](https://github.com/MICHITI/jcm_finance_tracker_releases/releases/download/v1.1.0/JMC_Finance_Tracker_Setup.exe)
- **SHA-256 Checksum**: `ba4918df0c4fd1bfbaf2d332a1ffd64bbdd4beb67b048d4aa2d304c3fffa7927`
- **Manifest**: [`update_manifest.json`](https://raw.githubusercontent.com/MICHITI/jcm_finance_tracker_releases/main/update_manifest.json)

---

### Verification (PowerShell)
You can verify the downloaded installer anytime using PowerShell:
```powershell
(Get-FileHash 'JMC_Finance_Tracker_Setup.exe' -Algorithm SHA256).Hash.ToLower()
# Expected: ba4918df0c4fd1bfbaf2d332a1ffd64bbdd4beb67b048d4aa2d304c3fffa7927
```

---

### Release Notes (v1.1.0)
- **Employee Data Synchronization**: Multi-computer real-time cloud sync for employee profiles, salaries, designations, and module access permissions.
- **Windows Desktop Auto Update System**: Background version checking, anonymous HTTPS installer downloading, SHA-256 verification, and smooth app restart.
- **API Integration Diagnostics**: Settings status dashboard verifying Supabase Cloud connectivity.
- **SQLite Database Protection**: Automated pre-migration and daily backups preserving all historical customer and loan records.

