# Slow Computer Troubleshooting Guide

## Overview

This guide provides structured troubleshooting steps for Windows devices experiencing slow performance.

Performance degradation is typically caused by excessive startup programs, high system resource usage, insufficient disk space, background processes, or system file corruption.

---

## Symptoms

Users may experience one or more of the following:

- Slow system startup (boot delay)
- Applications take a long time to open
- System freezing or intermittent lag
- High CPU or memory usage
- Low available disk space
- Delayed response when opening files or folders

---

## Possible Causes

Common causes include:

- Excessive startup applications
- Accumulated temporary or junk files
- Insufficient disk space
- High memory or CPU utilization
- Background processes consuming resources
- Outdated drivers
- System file corruption
- Fragmented or failing storage drive

---

## Troubleshooting Steps

### 1. Restart the Computer

Restarting clears temporary memory usage and resets background processes.

**Steps:**

- Click **Start → Power → Restart**

Monitor performance after restart.

---

### 2. Check System Resource Usage

1. Press `Ctrl + Shift + Esc` to open **Task Manager**
2. Review the **Processes** tab
3. Identify applications consuming high CPU, Memory, or Disk usage

If an application is consistently consuming excessive resources, consider closing or uninstalling it.

---

### 3. Disable Startup Applications

Reducing startup programs can significantly improve boot time.

**Steps:**

1. Open **Task Manager**
2. Select the **Startup** tab
3. Disable non-essential applications

Restart the system and evaluate performance.

---

### 4. Clean Temporary Files

#### Option A: Disk Cleanup

1. Open **Start Menu**
2. Search for **Disk Cleanup**
3. Select the system drive (usually `C:`)
4. Select unnecessary files
5. Click **OK**

#### Option B: Manual Cleanup

1. Press `Windows + R`
2. Enter `%temp%` and delete contents
3. Repeat for:
   - `temp`
   - `prefetch`

---

### 5. Verify Available Disk Space

Ensure at least 20% free space on the system drive.

1. Open **File Explorer**
2. Select **This PC**
3. Check available storage on drive `C:`

If storage is low, remove unused applications or large files.

---

### 6. Run System File Checker (Optional Advanced Step)

To check for system file corruption:

1. Open **Command Prompt** as Administrator
2. Run:
      `sfc /scannow`

Wait for the scan to complete and follow any repair instructions provided.

---

### 7. Check Disk Health (Optional)

To verify disk integrity:

1. Open **Command Prompt** as Administrator
2. Run:
      `chkdsk C: /f`
Restart if prompted.

---

## Escalation Criteria

Escalate to IT Support if:

- Performance does not improve after completing all steps
- CPU, memory, or disk usage remains abnormally high
- The system frequently freezes or crashes
- Disk health check reports errors
- There are signs of possible hardware failure (unusual noise, overheating)

Provide the following information when escalating:

- Device model
- Current CPU and memory usage percentage
- Available disk space
- Recent software or hardware changes
- Steps already performed