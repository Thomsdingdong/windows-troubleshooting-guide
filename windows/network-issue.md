# Network Connection Troubleshooting Guide

## Overview
This guide helps users troubleshoot Windows computers that cannot connect to a network or the internet.

---

## Symptoms
Common indicators of network connectivity issues include:

- **No Internet** status displayed
- Network icon shows a warning symbol
- Unable to open websites
- Internet-based applications cannot connect
- Windows Update fails

---

## Possible Causes
- LAN cable not properly connected
- Router or modem powered off
- ISP service disruption
- Network adapter issues
- Invalid IP configuration

---

## Troubleshooting Steps

### 1. Check Physical Connection
- Ensure the LAN cable is securely connected
- Check LAN indicator lights on the computer or router
- Restart the modem or router

---

### 2. Restart Network Adapter
1. Open **Control Panel**
2. Select **Network and Internet**
3. Click **Network Connections**
4. Right-click the network adapter
5. Select **Disable**, then **Enable**

---

### 3. Reset IP Configuration
1. Open **Command Prompt** as Administrator
2. Run the following commands:
        ipconfig /release
        ipconfig /renew
        ipconfig /flushdns

---

### 4. Run Network Troubleshooter
1. Open **Settings**
2. Select **Network & Internet**
3. Run **Network Troubleshooter**

---

## Escalation
Contact IT Support if:
- The computer still cannot connect to the network
- The network adapter is not detected
- LAN indicator lights are off
- Multiple devices experience the same issue

