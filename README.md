# Lab: Installing Windows 11 in Oracle VirtualBox

## 📅 Date
February 17, 2026

---

## 🎯 Objective
Set up a Windows 11 virtual machine using Oracle VirtualBox to create a safe environment for IT and cybersecurity labs without affecting the host operating system.

---

## 🖥️ Environment Details

| Component | Details |
|------------|---------|
| Host OS | Windows 11 |
| VM Platform | Oracle VirtualBox Manager |
| Guest OS | Windows 11 (64-bit ISO) |
| CPU | 3 vCPU |
| Memory | 4 GB (4096 MB) |
| Disk Size | 80 GB |
| Network Mode | NAT |

---

## 🔧 Steps Taken

1. Downloaded Windows 11 ISO from Microsoft official website.
2. Opened Oracle VirtualBox and selected **New Virtual Machine**.
3. Selected ISO image and OS edition.
4. Created username and password for unattended installation.
5. Assigned hardware resources:
   - 4 GB RAM
   - 2 CPU initially
   - 80 GB disk
6. Completed setup and started VM installation.

---

## ⚠️ Errors Encountered & Fixes

### Issue 1: Black screen during installation
- **Cause:** Graphics controller incompatibility.
- **Fix:** Changed Display → Graphics Controller from `VBoxSVGA` to `VMSVGA`.

### Issue 2: Installation screen went black again
- **Fix Attempt 1:** Saved VM state and reverted display settings.
- **Final Fix:** Increased CPU allocation from 2 to 3 processors and restarted VM.

---

## ✅ Outcome

- VirtualBox successfully detected the ISO file:
  `Win11_25H2_English_x64`
- Windows 11 installation completed successfully after troubleshooting display and CPU allocation issues.
- VM boots and operates normally.

---

## 💭 Reflection

Future improvements:
- Increase RAM allocation for better performance.
- Allocate additional CPU resources depending on lab requirements.
- Use this VM for future networking and cybersecurity labs.

---

## 📸 Screenshots

(Add installation screenshots here)
