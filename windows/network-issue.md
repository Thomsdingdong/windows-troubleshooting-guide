# Network Connection Troubleshooting Guide

## Overview

This guide assists users in diagnosing and resolving network connectivity issues on Windows devices, including problems related to local network access and internet connectivity.

---

## Symptoms

Common indicators of network issues include:

- **"No Internet"** status displayed
- Network icon shows a warning or disconnected symbol
- Unable to access websites
- Internet-based applications fail to connect
- Windows Update fails to download updates
- Limited or unidentified network message

---

## Possible Causes

Network connectivity issues may be caused by:

- Loose or disconnected LAN cable
- Router or modem powered off or malfunctioning
- ISP service disruption
- Disabled or malfunctioning network adapter
- Incorrect or invalid IP configuration
- DNS resolution issues
- Outdated or corrupted network drivers

---

## Troubleshooting Steps

### 1. Check Physical Connections

- Ensure the Ethernet cable is securely connected
- Verify Wi-Fi is enabled (if applicable)
- Check indicator lights on the router or modem
- Restart the modem and router (wait at least 30 seconds before reconnecting)

---

### 2. Verify Network Adapter Status

1. Open **Control Panel**
2. Select **Network and Internet**
3. Click **Network Connections**
4. Ensure the network adapter is enabled
5. If disabled, right-click and select **Enable**

If the adapter does not appear, check **Device Manager**:

- Open **Device Manager**
- Expand **Network adapters**
- Look for warning icons
- Update or reinstall the driver if necessary

---

### 3. Check IP Configuration

Open **Command Prompt** as Administrator and run:
                                                ipconfig

Verify that:
- The device has a valid IPv4 address
- The Default Gateway is assigned
- DNS server is present

If IP appears invalid (e.g., 192.254.x.x), renew the IP:
                                                ipconfig /release
                                                ipconfig /renew
                                                ipconfig /flushdns
---

### 4. Test Network Connectivity

Run the following commands:
                        ping 8.8.8.8
If successful, test DNS resolution:
                        ping google.com

- If IP ping works but domain ping fails, the issue may be DNS-related.
- If both fail, check router or ISP connection.

---

### 5. Run Windows Network Troubleshooter

1. Open **Settings**
2. Select **Network & Internet**
3. Click **Advanced network settings**
4. Run **Network Troubleshooter**

---

## Escalation Criteria

Escalate to IT Support if:

- The device cannot obtain a valid IP address
- The network adapter is not detected in Device Manager
- Multiple devices are experiencing the same issue
- Router/modem appears non-functional
- Ping tests fail consistently
- Issue persists after completing all troubleshooting steps

Provide the following information when escalating:

- Network type (Wi-Fi or Ethernet)
- IP configuration result (`ipconfig` output)
- Ping test results
- Number of affected devices
- Recent changes to network setup