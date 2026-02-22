# Blue Screen (BSOD) Troubleshooting Guide

## Overview

A Blue Screen of Death (BSOD) occurs when Microsoft Windows encounters a critical system error that forces the operating system to shut down unexpectedly. 

BSOD issues are commonly related to device drivers, hardware failures, corrupted system files, or recent system updates.

---

## Symptoms

Users may experience one or more of the following:

- A blue screen appears unexpectedly
- The system automatically restarts
- An error code is displayed on the screen
- The system becomes unstable or frequently crashes
- The issue occurs repeatedly during startup or regular use

---

## Possible Causes

Common causes of BSOD include:

- Corrupted or incompatible device drivers
- Failed or incomplete Windows updates
- Faulty or unstable RAM
- Hardware malfunction (SSD, motherboard, GPU)
- System overheating
- Corrupted system files

---

## Troubleshooting Steps

### 1. Record the Error Code

When the BSOD appears, note the error code displayed on the screen.

Examples:
- `CRITICAL_PROCESS_DIED`
- `MEMORY_MANAGEMENT`
- `IRQL_NOT_LESS_OR_EQUAL`

This information helps identify the root cause.

---

### 2. Restart the Computer

Restart the device and monitor whether the issue reoccurs.

If the problem does not reappear, it may have been a temporary system fault.

---

### 3. Check Recently Installed Drivers or Software

If the issue started after installing a driver or software:

1. Open **Device Manager**
2. Locate the recently installed driver
3. Right-click and select **Uninstall device**
4. Restart the computer

If necessary, install the latest stable driver from the official manufacturer website.

---

### 4. Run Windows Memory Diagnostic

To check for RAM-related issues:

1. Press `Win + R`
2. Type `mdsched.exe`
3. Select **Restart now and check for problems**

Allow the diagnostic process to complete.

---

### 5. Run System File Checker (SFC)

To scan for corrupted system files:

1. Open **Command Prompt** as Administrator
2. Run:
          sfc /scannow

Wait until the verification process reaches 100%.

---

### 6. Perform System Restore

If the issue started after a system update or configuration change:

1. Open **Control Panel**
2. Select **Recovery**
3. Click **Open System Restore**
4. Choose a restore point prior to the issue

---

## Escalation Criteria

Escalate to IT Support if:

- BSOD occurs repeatedly after troubleshooting
- The system fails to boot into Windows
- Memory diagnostics report hardware errors
- There are signs of hardware failure
- The device overheats frequently

Provide the following information when escalating:

- Error code
- Recent changes made to the system
- Diagnostic results
- Frequency of occurrence
