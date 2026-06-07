# 🔍 SatSec Scanner

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android-brightgreen?style=flat-square&logo=android" />
  <img src="https://img.shields.io/badge/Version-1.0.0-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Powered%20by-SatSec%20TM-red?style=flat-square" />
</p>

<p align="center">
  <b>A fast, native Android app for scanning and finding the best clean Cloudflare IPs — optimized for Iranian networks.</b>
</p>

---

## 📱 Download

👉 **[Download Latest APK](../../releases/latest)**

> Minimum Android version: **8.0 (Oreo)**

---

## ✨ Features

- 🔍 **TCP / TLS / HTTP** probe modes
- 📡 Scans all **15 official Cloudflare IP ranges** (~4 million IPs)
- 📊 Measures **latency** and **packet loss** for each IP
- ⚡ Fully **native Android** — no browser limitations, no CORS restrictions
- 🇮🇷 Optimized for **Iranian networks**
- 📋 **Copy IPs** with a single tap
- 📂 **Export results** as a text file
- 🔧 Highly **customizable** — set count, workers, timeout, ports, scan mode
- 💾 **Multi-port selection** — scan multiple ports simultaneously
- 🌐 Compatible with **VLESS / VMess / Trojan** configs

---

## 🚀 How to Install

1. Download the APK from the [Releases](../../releases) page
2. On your Android phone, go to **Settings → Security**
3. Enable **"Install from unknown sources"**
4. Open the downloaded APK and tap **Install**
5. Done! 🎉

---

## 📖 How to Use

1. Open the app
2. Tap **Start Scan**
3. Configure settings:
   - **IP Count** — how many IPs to scan (default: 500)
   - **Workers** — simultaneous connections (default: 50)
   - **Timeout** — response time limit (default: 3s)
   - **Port** — select one or multiple ports
   - **Mode** — TCP / TLS / HTTP
4. Tap **Start Scan** and wait
5. Results sorted by lowest latency
6. Tap any IP to copy it
7. Use **Save as File** or **Push to Worker** to export results

---

## 📂 APK Naming

| File | Description |
|------|-------------|
| `SatSecScanner-v1.0.0.apk` | Standard release |

---

## 🛠️ Built With

- **Kotlin** + **Jetpack Compose**
- Native Android TCP/TLS/HTTP socket probing
- No third-party scanning libraries
- Based on the original scanning logic of [SenPaiScanner](https://github.com/MatinSenPai/SenPaiScanner)

---

## 📋 Permissions

| Permission | Reason |
|------------|--------|
| `INTERNET` | Required for scanning Cloudflare IPs |

No other permissions needed. No data collection. No ads.

---

## ⚠️ Disclaimer

This app is intended for **educational and personal use only**. Use responsibly and in accordance with the laws of your country.

---

## 📜 License

MIT License — feel free to use, modify, and distribute Only with mentioning the original source ( us ) .

---

## 🙏 Credits

- Original scanner logic: [MatinSenPai/SenPaiScanner](https://github.com/MatinSenPai/SenPaiScanner)
- Cloudflare IP ranges: [cloudflare.com/ips](https://www.cloudflare.com/ips/)
- Powered by **SatSec TM**

---
<p align="center">Long Live Iran . Javid Shah</p>
<p align="center">Made with ❤️ by SatSec TM</p>
