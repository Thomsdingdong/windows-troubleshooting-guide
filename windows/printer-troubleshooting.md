# Printer Not Detected in Windows

## Overview

This guide assists users in resolving issues where a printer is not detected or appears offline in Windows.

The issue may occur after a system restart, Windows update, driver installation, or network configuration change.

---

## Symptoms

Users may experience one or more of the following:

- Printer does not appear in **Devices and Printers**
- Printer status shows as **Offline**
- Unable to print documents
- Printer not available in application print menu
- Error message: “Printer not found” or similar

---

## Possible Causes

Common causes include:

- Printer powered off
- USB cable disconnected or faulty
- Printer not connected to the network
- Corrupted or missing printer driver
- Print Spooler service stopped
- Incorrect default printer selection
- Network discovery disabled

---

## Troubleshooting Steps

### 1. Verify Printer Power and Connection

- Ensure the printer is powered on
- Check USB cable connection (for local printers)
- Confirm Wi-Fi or Ethernet connection (for network printers)
- Restart the printer

If network-based, ensure the printer and computer are on the same network.

---

### 2. Restart Print Spooler Service

1. Press `Win + R`
2. Type `services.msc`
3. Locate **Print Spooler**
4. Right-click and select **Restart**

If the service fails to start, check for system errors.

---

### 3. Check Printer Status in Settings

1. Open **Settings**
2. Navigate to **Bluetooth & devices**
3. Select **Printers & scanners**
4. Confirm the printer appears in the list

If listed as **Offline**, right-click and disable “Use Printer Offline.”

---

### 4. Reinstall or Update Printer Driver

1. Open **Device Manager**
2. Expand **Print queues**
3. Right-click the printer
4. Select **Uninstall device**
5. Restart the computer
6. Download and install the latest driver from the manufacturer's website

---

### 5. Add Printer Manually

If the printer is not automatically detected:

1. Go to **Settings**
2. Select **Printers & scanners**
3. Click **Add device**
4. If not detected, choose **Add manually**
5. Enter the printer IP address (for network printers) if required

---

### 6. Test Network Connectivity (For Network Printers)

Open **Command Prompt** and run:
                                ping <printer_IP_address>

If the ping fails, verify network configuration or router settings.

---

## Escalation Criteria

Escalate to IT Support if:

- Printer remains undetected after driver reinstallation
- Print Spooler service repeatedly stops
- Network printer cannot be reached via IP address
- Multiple users cannot access the same printer
- Hardware error indicators appear on the printer

Provide the following information when escalating:

- Printer model
- Connection type (USB or Network)
- Error message displayed
- IP address (for network printer)
- Steps already performed