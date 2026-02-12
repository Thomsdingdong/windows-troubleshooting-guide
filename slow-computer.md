# Slow Computer Troubleshooting Guide

## Overview
This guide provides troubleshooting steps for Windows computers experiencing slow performance. Performance issues are commonly related to system resource usage, startup applications, or accumulated temporary files.

---

## Symptoms
Common indicators of slow computer performance include:

- Slow system startup (booting)
- Applications take a long time to open
- System freezing or lagging
- High CPU or memory usage
- Low available disk space

---

## Possible Causes
- Too many startup applications
- Accumulated temporary files
- Low disk space
- High memory usage
- System has not been restarted for a long time

---

## Troubleshooting Steps

### 1. Restart the Computer
Restarting clears temporary memory usage and stops unnecessary background processes.

**Steps:**
- Click **Start → Power → Restart**

---

### 2. Disable Startup Applications
Reducing startup applications can improve boot time and overall system performance.

**Steps:**
1. Press `Ctrl + Shift + Esc` to open **Task Manager**
2. Select the **Startup** tab
3. Select unnecessary applications
4. Click **Disable**

---

### 3. Remove Temporary Files
Cleaning temporary files can free up disk space and improve performance.

#### Using Disk Cleanup
1. Open **Start Menu**
2. Type **Disk Cleanup**
3. Select the system drive (usually `C:`)
4. Select files to delete
5. Click **OK**

#### Manually Removing Temp Files
1. Press `Windows + R`
2. Type `%temp%` and delete the files
3. Repeat the process with:
   - `temp`
   - `prefetch`

---

### 4. Check Disk Space
Ensure the system drive has at least 20% free space available.

**Steps:**
1. Open **File Explorer**
2. Select **This PC**
3. Check available space on drive `C:`

---

## Escalation
Contact IT Support if:
- The computer remains slow after completing all steps
- CPU or memory usage remains abnormally high
- There are signs of possible hardware failure
