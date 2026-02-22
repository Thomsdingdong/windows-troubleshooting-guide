# Windows Login Issue Troubleshooting Guide

## Overview

This guide assists users in resolving login-related issues in Microsoft Windows environments, including local and domain-based authentication problems.

Login issues may involve incorrect credentials, profile corruption, domain connectivity failures, or system instability.

---

## Symptoms

Users may experience one or more of the following:

- Message: **"Password incorrect"**
- Message: **"We can't sign in to your account"**
- Login loop returning to the login screen
- Black screen after entering credentials
- System freeze after login
- Keyboard not responding at login screen
- Message indicating that the domain is unavailable

---

## Possible Causes

Common causes include:

- Incorrect password entry
- Faulty or unresponsive keyboard
- Corrupted user profile
- Graphics driver issues
- Domain controller unreachable
- Network connectivity problems
- Malware or system corruption

---

## Troubleshooting Steps

### 1. Verify Keyboard Functionality

Ensure the keyboard is functioning correctly.

- Try using a different keyboard
- Use the **On-Screen Keyboard** from the **Ease of Access** icon on the login screen
- Confirm that Caps Lock or Num Lock is not affecting password entry

---

### 2. Attempt Login Using Local Account

If domain login fails, attempt login with a local account.

1. Select **Other user** on the login screen
2. Enter the username in the following format:
                                            .\username

3. Enter the local account password

If login succeeds, the issue may be related to domain connectivity.

---

### 3. Check Network Connection (For Domain Environment)

If using a domain account:

- Ensure the device is connected to the corporate network
- Verify Ethernet or Wi-Fi connection
- If remote, confirm VPN connection is active before login

---

### 4. Use Ctrl + Alt + Del

If the login screen becomes unresponsive:

- Press `Ctrl + Alt + Del`
- Select **Restart**
- If available, open **Task Manager** to check for abnormal processes

---

### 5. Perform a Forced Restart

If the system is frozen:

- Press and hold the power button for 5–10 seconds
- Wait a few seconds
- Turn the computer back on

---

### 6. Refresh Graphics Driver (Black Screen After Login)

If a black screen appears after login:

Press:
        `Windows + Ctrl + Shift + B`

The screen may flicker briefly as the graphics driver resets.

---

### 7. Boot into Safe Mode (If Issue Persists)

If login continues to fail:

1. Restart the computer
2. Interrupt startup three times to enter **Advanced Startup**
3. Select:
   - **Troubleshoot**
   - **Advanced options**
   - **Startup Settings**
   - **Restart**
4. Choose **Safe Mode**

Attempt login in Safe Mode to isolate driver or software conflicts.

---

## Escalation Criteria

Escalate to IT Support if:

- Unable to log in using both local and domain accounts
- User profile appears corrupted
- The device cannot connect to the domain network
- Keyboard fails at BIOS level
- Safe Mode login fails
- Repeated login loop persists after troubleshooting

Provide the following information when escalating:

- Error message displayed
- Account type (local or domain)
- Network status
- Recent system changes or updates
- Steps already performed