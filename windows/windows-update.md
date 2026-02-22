# Windows Update Failure Troubleshooting Guide

## Overview

This guide provides structured troubleshooting steps for resolving Windows Update failures.

Failed updates may prevent the system from receiving critical security patches, feature improvements, and stability fixes.

---

## Symptoms

Users may experience one or more of the following:

- Windows Update stuck at 0% or 100%
- Update fails with an error code
- Repeated update failures
- System repeatedly prompts for restart
- Update installation freezes
- Error messages such as:
  - `0x80070002`
  - `0x80070005`
  - `0x8024402C`

---

## Possible Causes

Common causes include:

- Corrupted update cache
- Interrupted update process
- Insufficient disk space
- Damaged system files
- Windows Update service malfunction
- Network connectivity issues

---

## Troubleshooting Steps

### 1. Restart the Computer

Restart the device and attempt the update again.

Temporary update conflicts may resolve after reboot.

---

### 2. Run Windows Update Troubleshooter

1. Open **Settings**
2. Navigate to **System → Troubleshoot**
3. Select **Other troubleshooters**
4. Run **Windows Update**

Allow the process to complete and apply suggested fixes.

---

### 3. Restart Windows Update Services

1. Press `Win + R`
2. Type `services.msc`
3. Restart the following services:
   - **Windows Update**
   - **Background Intelligent Transfer Service (BITS)**

Retry Windows Update after restarting services.

---

### 4. Clear the SoftwareDistribution Folder

Corrupted update cache may cause repeated failures.

1. Open **Command Prompt** as Administrator
2. Run:
        `net stop wuauserv`
        `net stop bits`
3. Navigate to:
        `C:\Windows\SoftwareDistribution`
4. Delete all contents inside the folder
5. Restart services:
        `net start wuauserv`
        `net start bits`
Retry the update.

---

### 5. Run System File Checker (SFC)

To repair corrupted system files:

1. Open **Command Prompt** as Administrator
2. Run:
        `sfc /scannow`
Wait until the process completes.

---

### 6. Run DISM Tool (Advanced Repair)

If the issue persists:

1. Open **Command Prompt** as Administrator
2. Run:
        `DISM /Online /Cleanup-Image /RestoreHealth`
After completion, restart the system and attempt the update again.

---

## Escalation Criteria

Escalate to IT Support if:

- Update continues to fail after clearing the cache
- DISM or SFC reports unrecoverable errors
- Error codes persist
- System becomes unstable after update attempts
- Multiple devices experience the same update failure

Provide the following information when escalating:

- Windows version and build number
- Error code displayed
- Available disk space
- Network type (LAN/Wi-Fi)
- Steps already performed