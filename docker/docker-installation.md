# Docker Desktop Installation Guide (Windows)

## Overview

This guide provides step-by-step instructions for installing Docker Desktop on Windows and verifying a successful installation.

Docker Desktop enables users to build, run, and manage containerized applications locally using Docker Engine and WSL 2.

---

## System Requirements

Ensure the following requirements are met before installation:

- Windows 10 (64-bit, version 21H2 or higher) or Windows 11
- Administrator privileges
- Stable internet connection
- Virtualization enabled in BIOS
- Windows Subsystem for Linux 2 (WSL 2) enabled

To verify WSL status, open PowerShell and run:
                                                `wsl --status`

---

## Installation Steps

### 1. Download Docker Desktop

1. Navigate to:  
   https://www.docker.com/products/docker-desktop/
2. Click **Download for Windows**

---

### 2. Run the Installer

1. Execute the downloaded installer
2. Follow the installation wizard
3. Ensure **Use WSL 2 instead of Hyper-V** is selected (recommended)
4. Allow the installer to enable required Windows features if prompted
5. Restart the computer if required

---

### 3. Launch Docker Desktop

1. Open **Docker Desktop**
2. Wait until the status shows **Docker Engine running**
3. Ensure no error notifications appear

---

## Verification Steps

### 1. Verify Docker Version

Open **Command Prompt** or **PowerShell** and run:
                                                    `docker --version`
A version number should be displayed.

---

### 2. Verify Docker Engine

Run:
    `docker info`
If Docker is running properly, system information about containers and images will appear.

---

### 3. Run Test Container

Run the following command:
                        `docker run hello-world`
If successful, the terminal will display:
                        **Hello from Docker!**
This confirms Docker is functioning correctly.

---

## Common Issues

### Docker Engine Not Starting

- Ensure virtualization is enabled in BIOS
- Verify WSL 2 is installed and updated
- Restart Docker Desktop

### WSL Installation Error

Run the following command in PowerShell (Administrator):
                                                        `wsl --install`
Restart the system afterward.

---

## Escalation Criteria

Escalate to IT Support if:

- Docker Desktop fails to start after reinstalling
- WSL cannot be installed or enabled
- `docker info` returns engine connection errors
- Virtualization is unavailable in BIOS

Provide the following details when escalating:

- Windows version and build number
- Docker Desktop version
- Screenshot of error message
- Output of `docker --version`
- Output of `docker info`
- Steps already performed