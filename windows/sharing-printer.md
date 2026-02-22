# Printer Sharing Guide (Windows)

## Overview

This guide explains how to add and configure a shared printer in a Windows environment. 

A shared printer may be:
- Connected directly to another computer and shared over the network, or
- A network printer accessible via IP address.

This document covers both scenarios.

---

## Prerequisites

Before proceeding, ensure:

- The printer is powered on
- The printer is properly connected (USB or Network)
- The host computer (if shared via PC) is powered on
- The client computer is connected to the same network
- You know the printer name or IP address
- Required permissions are available

---

## Method 1: Add a Shared Printer from Another Computer

Use this method if the printer is connected to a host computer and shared.

### Steps:

1. Open **Control Panel**
2. Select **Devices and Printers**
3. Click **Add a printer**
4. If not detected, select **The printer that I want isn't listed**
5. Choose **Select a shared printer by name**
6. Enter the shared printer path:
7. Click **Next**
8. Install the driver if prompted.

---

## Method 2: Add Printer Using IP Address (Network Printer) 

Use this method if the printer has its own IP address.

### Steps:

1. Open **Control Panel**
2. Select **Devices and Printers**
3. Click **Add a printer**
4. Choose **The printer that I want isn't listed**
5. Select **Add a printer using a TCP/IP address or hostname**
6. Enter the printer’s IP address (e.g., `192.168.1.10`)
7. Click **Next**
8. Install the appropriate driver when prompted.

---

## Verification After installation:

- Open **Devices and Printers** 
- Confirm the printer appears in the list 
- `Right-click` the printer
- Select **Printer properties** 
- Click **Print Test Page** Ensure the test page prints successfully.

---

## Verification After installation:

- Open **Devices and Printers** 
- Confirm the printer appears in the list 
- Right-click the printer 
- Select **Printer properties** 
- Click **Print Test Page** Ensure the test page prints successfully.

---

## Troubleshooting If the printer cannot be added:

- Verify the printer IP address by running: ` ping <printer_IP_address> `
- Confirm both devices are on the same network 
- Check if network discovery is enabled 
- Restart the Print Spooler service 
- Ensure firewall settings are not blocking printer sharing.

---

## Escalation Criteria Escalate to IT Support if:

- The shared printer path cannot be accessed 
- The printer IP address is unreachable 
- Driver installation repeatedly fails 
- Multiple users are unable to connect 
- The printer prints from the host device but not from client devices Provide the following information when escalating: 
    - Printer model
    - Connection type (Shared via PC or Direct Network)
    - Printer IP address (if applicable)
    - Error message displayed 
- Steps already performed