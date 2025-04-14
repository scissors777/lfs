# 🐧 Linux From Scratch (LFS) Project

Welcome to my **Linux From Scratch** project! This repository documents my journey building a custom Linux system entirely from source, following the LFS guide. The project serves as a deep dive into the inner workings of Linux and is a personal initiative to sharpen my system-level skills.

---

## 📚 Project Purpose

This project is primarily for:

- **Learning:** Understanding how a Linux system is built from the ground up
- **Demonstration:** Showcasing my Linux administration and troubleshooting skills
- **Documentation:** Keeping detailed logs, notes, and scripts for reproducibility

---

## 📁 Project Structure

```
/
├── 00-bootstrap/      # Host preparation and toolchain bootstrap
├── 01-temp-tools/     # Temporary system tools (Chapter 5)
├── 02-final-system/   # Final system build (Chapter 6)
├── 03-config/         # Configuration files and boot scripts
├── 04-kernel/         # Linux kernel compilation
├── 05-bootable/       # System setup for booting
├── logs/              # Build logs for troubleshooting
├── scripts/           # Helper scripts and build automation
└── README.md          # This file
```

---

## 🛠️ Tools & Environment

- **LFS Version:** 12.3
- **Host System:** AlmaLinux 9.5
- **Architecture:** x86_64
- **Build Method:** Manual via chroot
- **Kernel Version:** 6.x.x

---

## ✅ Progress Checklist

- [*] Host System Ready
- [ ] Toolchain Compiled
- [ ] Temporary Tools Built
- [ ] Final System Installed
- [ ] Kernel Built
- [ ] Bootable Image Created
- [ ] System Booted Successfully

---

## 📌 Notes

- All commands are documented step-by-step.
- Build logs are stored in the `logs/` directory.
- Any deviations from the LFS book are explained with reasons.

---

## 📦 Resources

- [Linux From Scratch Official Book](https://www.linuxfromscratch.org/lfs/)
- [Beyond Linux From Scratch](https://www.linuxfromscratch.org/blfs/)
- [LFS Hints & Community](https://www.linuxfromscratch.org/hints/)

---
## 📄 License

This project is open-source and licensed under the GPLv3 License.
