# Raspi-cloud-storage
# 🌐 Raspberry Pi Local Cloud Storage using Nextcloud & Tailscale

This project demonstrates how to build your **personal cloud storage system** using a **Raspberry Pi**, a **local hard disk**, and **Nextcloud**, with secure global access enabled via **Tailscale** — all without relying on port forwarding!

---

## 🚀 Project Overview

Using a Raspberry Pi, I created a fully functional local cloud system by:

1. **Mounting a local hard disk** to the Raspberry Pi.
2. Installing and configuring **Nextcloud** for cloud storage management.
3. Using **MariaDB** for database management.
4. Adding trusted IPs and domains in Nextcloud for secure access.
5. Installing **Tailscale** to access the setup from anywhere securely (even on different networks).
6. Running a local server and configuring **Nextcloud's trusted domains** with the generated Tailscale address.

---

## 🧰 Tech Stack

- 🐧 Raspberry Pi (any model with network + USB support)
- 💾 External Hard Disk (NTFS or ext4 recommended)
- ☁️ [Nextcloud](https://nextcloud.com/)
- 🛢️ MariaDB (MySQL alternative)
- 🔐 [Tailscale](https://tailscale.com/) (for VPN + remote access)
- 🧠 Apache2, PHP, Linux shell commands

---

#🌍 Benefits
🧠 Self-hosted and privacy-focused

🌐 Access from anywhere securely via Tailscale

💸 No need for port forwarding or cloud hosting services

🧩 Modular setup (you can expand storage, users, features)


