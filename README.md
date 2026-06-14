# ⚡ Bad hunting ⚡
**A single-page, browser-based recon dashboard for Bug Bounty Hunters and Red Teamers.**

Bad hunting provides one-click access to smart dorking, archives, subdomain/DNS tools, cloud/config search, and secret/token scanners for any given target. Everything runs client-side; no backend required.

🌐 **Live Demo:** [https://yasserr257.github.io/Bad-Hunting/](https://yasserr257.github.io/Bad-Hunting/)

---

## 🎯 Features

* **🧠 Smart Dorking:** Pre-built Google, Bing, Yandex, and DuckDuckGo dorks for finding login pages, leaked configs, API keys, and sensitive files.
* **📂 Archives & History:** Quick queries for Wayback Machine, AlienVault OTX, URLScan, and VirusTotal.
* **🌐 Subdomains & DNS:** Integration with crt.sh, SecurityTrails, Netlas, and Google Dig (ANY/CNAME for takeover checks).
* **☁️ Cloud & Config:** Google Drive/Groups discovery and CSP Evaluator.
* **🔑 Secrets & Tokens:** JWT auditor, JS secret scanners, and favicon hash lookups.
* **📖 Dork References & External Engines:** Direct access to LeakIX, Shodan, FOFA Search, and Chaos (ProjectDiscovery).

---

## 🔑 VirusTotal API Key

The VirusTotal lookups require a personal API key. 
1. Enter it once in the password field at the top of the dashboard.
2. It is **saved securely only in your browser's `localStorage`** and is never transmitted anywhere except directly to VirusTotal's API.
3. *Don't have one? Get a free key at [virustotal.com](https://www.virustotal.com/).*

---

## 🚀 Usage

1. Open the page (locally by double-clicking `index.html` or via GitHub Pages).
2. Enter a target domain or IP address in the main input field.
3. *(Optional)* Enter your VirusTotal API key.
4. Click any tool button — it will automatically open a new tab with the relevant query pre-filled for your target.

---


## ⚠️ Disclaimer

**For use on authorized targets only** (bug bounty programs, your own assets, or targets where you have explicit written permission). The author is not responsible for any misuse or damage caused by this tool.

---

## 👤 Author

Created and maintained by **BadYasser** ([@Yasserr257](https://github.com/Yasserr257)).
