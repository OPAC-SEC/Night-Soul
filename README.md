# ☠️ Night-Soul ☠️
*The Ultimate DoS Arsenal – Unleash Chaos, Test Your Limits*

![Status](https://img.shields.io/badge/STATUS-UNSTOPPABLE-red)

**Night-Soul** is a next-level Denial-of-Service (DoS) framework engineered for elite red team operatives and penetration testers. This beast pushes systems to their breaking points by launching multi-vector attacks—from raw TCP SYN floods (powered by Scapy) to advanced HTTP/HTTPS request floods and relentless Slowloris strikes.

> **⚠️ LEGAL NOTICE:** This weapon is for **authorized cybersecurity testing, red teaming, and penetration testing only.** Unauthorized use is illegal and will be met with full force. Use responsibly.

---

## ⚡ FEATURES & VIRTUOSITY

- **🚀 Multi-Mode Attacks:**  
  - **Basic DoS Attack:** Rain down randomized HTTPS requests to overwhelm targets.  
  - **Firewall Bypass DoS Attack:** Merge raw SYN floods with HTTPS strikes to break through basic defenses.  
  - **Full Security Bypass DoS Attack:** Employ payload obfuscation (XOR + Base64), dynamic spoofing, and randomized injections to dismantle advanced security.  
  - **Slowloris Attack:** Establish and maintain persistent, slow connections to exhaust server resources.

- **🔫 Raw SYN Flooding:** Uses Scapy to deliver low-level TCP SYN packets (requires admin/root privileges).

- **🌐 HTTPS Request Flooding:** Leverages custom SSL contexts and randomized HTTP headers to simulate legitimate traffic while causing havoc.

- **🛡 Payload Obfuscation:**  
  - **XOR Encoding:** Camouflages payloads with a secret key.  
  - **Base64 Encoding:** Encodes data to evade simple inspection.

- **🎭 Randomized HTTP Headers:** Generates dynamic User-Agents, spoofed IP addresses, and custom headers to bypass filters.

- **🕵️‍♂️ Proxy Support:** Integrates SOCKS5 and HTTP proxies (load extra proxies from `proxies.txt`) for stealth and anonymity.

- **⚙️ High Concurrency:** Utilizes Python's ThreadPoolExecutor to launch thousands of threads/connections, limited only by your system's capabilities.

- **💥 Killer Visuals:** Displays an epic ASCII banner (via PyFiglet) and colorful logs (thanks to Colorama) to keep you in the zone.

---

## 🛠️ REQUIREMENTS

- **Python 3.x**  
- [Scapy](https://scapy.net/)  
- [Requests](https://docs.python-requests.org/)  
- [PyFiglet](https://github.com/pwaller/pyfiglet)  
- [Colorama](https://github.com/tartley/colorama)  
- Standard libraries: `socket`, `ssl`, `base64`, `threading`, `concurrent.futures`, etc.

*⚠️ Note: For raw SYN floods, run with elevated privileges (e.g., `sudo python dark_reaper_soul.py` on Linux). Boost your open file limits (`ulimit -n 65535`) for massive concurrency.*

---

## 🚀 INSTALLATION & SETUP

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/OPAC-SEC/Night-soul.git
   cd Night-soul
   ```

---

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

---

3. **⚠️ DISCLAIMER**

    Night-Soul is a potent tool designed solely for ethical cybersecurity testing and penetration testing. Use this tool only on systems where you have
   explicit permission to conduct tests. Unauthorized use can result in serious legal consequences. Always stay within the boundaries of the law.

---   

4. **👤 CREATED BY**
   **AbhayKumar Patel (@OPAC-SEC)**  
    
   Follow my chaos on GitHub and join the revolution.

   ---
## 📸 Screenshots
![Tool Image](https://github.com/OPAC-SEC/Night-Soul/blob/0d3487db9bf88d7b7436a32efb88b5ffc8050015/images/tool%20image.png)  
![Attack Mode](https://github.com/OPAC-SEC/Night-Soul/blob/0d3487db9bf88d7b7436a32efb88b5ffc8050015/images/attck%20mode.png)  
![Terminal Output 2](https://github.com/OPAC-SEC/Night-Soul/blob/0d3487db9bf88d7b7436a32efb88b5ffc8050015/images/terminal%20mode.png) 
![Terminal Output](https://github.com/OPAC-SEC/Night-Soul/blob/f48b92a9cc147afd1b61f66ea2af19d4b03109b2/images/terminal%20output.png)

