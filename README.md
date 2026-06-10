# ip.py_new
New version ip.py


# 🚀 Mahan IP Tool

A fast, cross-platform network utility written in Python for terminal use on **Windows, Linux, and macOS**.

## ✨ Features
- **Ping Test** — 4-step ping check with average latency calculation
- **IP Info** — get country, city, ISP, and organization details for an IP
- **Port Scan** — scan common/sensitive ports
- **Find Clean IP** — scan a `/24` range and save active IPs into `clean_ips.txt`
- **Range Scan** — manually scan a selected IP range
- **Cross-Platform** — works on Windows, Linux, and macOS
- **Threaded Scanning** — faster scans using controlled multithreading
- **Safe File Writing** — uses locking to avoid write conflicts

## 📦 Requirements
Install Python 3 and the required package:
```bash
pip install requests

Or with requirements.txt:

pip install -r requirements.txt


▶️ Run

python ip.py


📁 Output
Active IPs found during clean scan are saved in:

clean_ips.txt

⚙️ Notes
Ping logic is automatically adjusted for your operating system
Designed for educational, admin, and personal network testing
Use only on systems and networks you own or have permission to test
👨‍💻 Developer
Mahan

🤖 Assistant
GPT

📜 License
MIT License (optional — you can add a LICENSE file later)
