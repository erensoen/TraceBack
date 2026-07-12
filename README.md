# 🔍 TraceBack: Advanced Asynchronous OSINT & Username Intelligence Engine

<p align="center">
  <img src="https://img.shields.io/github/stars/erensoen/TraceBack?style=for-the-badge&color=711c91&labelColor=000000" alt="Stars">
  <img src="https://img.shields.io/github/forks/erensoen/TraceBack?style=for-the-badge&color=ea00d9&labelColor=000000" alt="Forks">
  <img src="https://img.shields.io/github/license/erensoen/TraceBack?style=for-the-badge&color=0abdc6&labelColor=000000" alt="License">
  <img src="https://img.shields.io/badge/Python-3.10%2B-0abdc6?style=for-the-badge&logo=python&labelColor=000000" alt="Python">
</p>

<p align="center">
  <b>TraceBack</b> is a next-generation, high-speed Open Source Intelligence (OSINT) tool designed to track digital footprints across social networks, forums, and web platforms using only a username. Built on a modern asynchronous architecture, it bypasses heavy anti-bot mechanisms to deliver deep profile intelligence.
</p>

---

## ⚡ Key Capabilities (Ana Kabiliyetler)

*   🚀 **High-Performance Async Engine:** Leverages `asyncio` to execute hundreds of platform audits simultaneously, cutting down scanning time from minutes to mere seconds.
*   🛡️ **Advanced Anti-Bot Shield (`route_interceptor`):** Implements a customized request filter via `Playwright`. It drops tracking scripts, advertisement networks, and cookie walls on the fly to mimic organic human behavior and bypass strict Cloudflare/bot protections.
*   📍 **Deep Data Extraction (Regex Engine):** Unlike traditional tools that only verify "Account Exists", TraceBack penetrates the DOM using `BeautifulSoup` to extract deeply nested details like location indicators, local license plates, flags, and custom bio patterns.
*   🎭 **Modern Web Compatibility:** Fully supports single-page applications (SPAs) built on React, Vue, and Next.js by rendering the actual javascript environment rather than relying on raw HTTP requests.

---

## 📸 Demo & Terminal Interface

<p align="center">
  <img src="demo.gif" alt="TraceBack Terminal Workflow" width="85%">
</p>

---

## 🛠️ Installation & Setup (Kurulum)

### Prerequisites
Make sure you have Python 3.10+ installed on your system.

```bash
# Clone the repository
git clone [https://github.com/yourusername/TraceBack.git](https://github.com/yourusername/TraceBack.git)

# Navigate into the project directory
cd TraceBack

# Install required dependencies
pip install -r requirements.txt

# Install headless browser binaries for Playwright
playwright install
