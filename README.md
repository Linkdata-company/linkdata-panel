# ![LinkData Logo](https://www.linkdata.com/images/logo.webp =50x50) LinkData Panel

**Lightweight and powerful control panel for the modern web**

---

## 🌐 Links

- [LinkData.com](https://www.linkdata.com/)
- [Blog](https://blog.linkdata.com/)
- [Forum](https://forum.linkdata.com/)

---

## 📷 Screenshot

![LinkData Panel Web Interface](https://www.linkdata.com/images/logo.webp)

---

## Welcome!

**LinkData Panel** is designed to provide administrators with an easy-to-use web and command line interface. Quickly deploy and manage:

- Web domains
- Mail accounts
- DNS zones
- Databases  

All from one central dashboard — without manually configuring individual components.

---

## ⚡ Features and Services

| Feature | Description |
|---------|-------------|
| **Web Servers** | Apache2 and NGINX with PHP-FPM |
| **PHP Support** | Multiple PHP versions (5.6 → 8.4, 8.3 default) |
| **DNS Management** | DNS Server (Bind) with clustering capabilities |
| **Mail Services** | POP/IMAP/SMTP with Anti-Virus, Anti-Spam, and Webmail (ClamAV, SpamAssassin, Sieve, Roundcube) |
| **Database Support** | MariaDB/MySQL and/or PostgreSQL databases |
| **SSL Certificates** | Let's Encrypt SSL support with wildcard certificates |
| **Security** | Firewall with brute-force detection and IP lists (iptables, fail2ban, ipset) |

---

## 🖥️ Supported Platforms and Operating Systems

- Debian 12
- Debian 11
- Ubuntu 24.04 LTS
- Ubuntu 22.04 LTS
- Ubuntu 20.04 LTS

---

## ⚠️ Notes

- LinkData Panel does **not** support 32-bit operating systems.  
- Running on OpenVZ 7 or lower may cause DNS/firewall issues. For VPS we recommend **KVM** or **LXC**.

---

## 🚀 Installing LinkData Panel

> **NOTE:** Must be installed on a fresh OS for best results.

**Step 1: Log in**
```bash
ssh root@your.server


