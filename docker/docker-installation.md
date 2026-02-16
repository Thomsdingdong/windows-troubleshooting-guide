# Docker Desktop Installation Guide (Windows)

## Overview
This guide explains how to install Docker Desktop on Windows and verify that Docker is running correctly.

Docker Desktop allows users to build, run, and manage containers locally.

---

## Prerequisites
Before installing Docker Desktop, ensure:

- Windows 10 or Windows 11 (64-bit)
- Administrator access
- Internet connection
- Virtualization enabled in BIOS

---

## Installation Steps

### 1. Download Docker Desktop
1. Open https://www.docker.com/products/docker-desktop/
2. Click **Download for Windows**

---

### 2. Install Docker Desktop
1. Run the installer
2. Follow the installation wizard
3. Allow Docker to install **Windows Subsystem for Linux (WSL)** if prompted
4. Restart the computer if required

---

### 3. Start Docker Desktop
1. Open Docker Desktop
2. Wait until Docker Engine is running

---

## Verification

Open terminal and run:
                `docker --version`
                
Then run:
                `docker run hello-world` 

If the installation is successful, the terminal will display:

                Hello from Docker!

---

## Conclusion
Docker Desktop is now successfully installed and ready to use.


                
