<h1 align="center"><a href="https://www.linkdata.com/">LinkData Panel</a></h1>

![LinkData Panel Web Interface screenshot](https://www.linkdata.com/images/logo.webp)

<h2 align="center">Lightweight and powerful control panel for the modern web</h2>

<p align="center"><strong>Latest stable release:</strong> Version 1.9.4 | <a href="https://github.com/Linkdata-company/linkdata-panel/blob/release/CHANGELOG.md">View Changelog</a></p>

<p align="center">
	<a href="https://www.linkdata.com/">LinkData.com</a> |
	<a href="https://blog.linkdata.com/">Blogs</a> |
	<a href="https://forum.linkdata.com/">Forum</a>
	<br/><br/>
	<a href="https://github.com/Linkdata-company/linkdata-panel/actions/workflows/lint.yml">
		<img src="https://github.com/Linkdata-company/linkdata-panel/actions/workflows/lint.yml/badge.svg" alt="Lint Status"/>
	</a>
	<a href="https://img.shields.io/badge/Community-Support-blue">
		<img src="https://img.shields.io/badge/Community-Support-blue" alt="Support"/>
	</a>
</p>

---

## **Welcome!**

**LinkData Panel** is designed to provide administrators with an easy-to-use web and command line interface, enabling them to quickly deploy and manage web domains, mail accounts, DNS zones, and databases from one central dashboard — without the hassle of manually deploying and configuring individual components or services.

---

## 💰 Donate

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=ST87LQH2CHGLA)<br /><br />
- Bitcoin : `bc1q48jt5wg5jaj8g9zy7c3j03cv57j2m2u5anlutu`  
- Ethereum : `0xfF3Dd2c889bd0Ff73d8085B84A314FC7c88e5D51`  
- Binance : `bnb1l4ywvw5ejfmsgjdcx8jn5lxj7zsun8ktfu7rh8`  
- Smart Chain : `0xfF3Dd2c889bd0Ff73d8085B84A314FC7c88e5D51`  

---

## ⚡ Features and Services

- Apache2 and NGINX with PHP-FPM
- Multiple PHP versions (5.6 → 8.4, 8.3 default)
- DNS Server (Bind) with clustering capabilities
- POP/IMAP/SMTP mail services with Anti-Virus, Anti-Spam, and Webmail (ClamAV, SpamAssassin, Sieve, Roundcube)
- MariaDB/MySQL and/or PostgreSQL databases
- Let's Encrypt SSL support with wildcard certificates
- Firewall with brute-force detection and IP lists (iptables, fail2ban, ipset)

---

## 🖥️ Supported platforms and operating systems

- **Debian:** 12, 11  
- **Ubuntu:** 24.04 LTS, 22.04 LTS, 20.04 LTS  

**NOTES:**  
- LinkData Panel does **not** support 32-bit operating systems.  
- Running on OpenVZ 7 or lower may cause DNS/firewall issues. For VPS we recommend **KVM** or **LXC**.  

---

## 🚀 Installing LinkData Panel

> **NOTE:** Must be installed on a fresh OS for best results.  

### Step 1: Log in
```bash
ssh root@your.server
