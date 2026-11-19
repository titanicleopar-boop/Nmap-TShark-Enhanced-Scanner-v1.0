

# 🛡️ NMAP-TSHARK ENHANCED SCANNER

### ADVANCED NETWORK RECONNAISSANCE FRAMEWORK

**Developed by ByRooT**

**Intelligent Port Detection | Traffic Analysis | False-Positive Filtering**

<img width="70%" alt="Nmap-TShark Enhanced Scanner Output" src="https://github.com/user-attachments/assets/5040d231-ccf0-4f1c-9b6c-08c7c6962c1b" />

<img width="30%" alt="Nmap-TShark Enhanced Scanner Output" src="https://github.com/user-attachments/assets/f67e4a19-990e-450a-8cd7-4932d6042f1c" />

https://www.youtube.com/watch?v=SA3qvTmIz1s

### 🎯 Advanced Port Verification & False-Positive Filtering

The scanner combines Nmap scanning capabilities with Wireshark/TShark traffic analysis to improve port detection reliability and distinguish genuine open-port responses from potentially misleading results.

- **False-Positive Detection:** Identifies potentially misleading port scan results.
- **Port Verification:** Performs additional analysis to validate detected port states.
- **Traffic-Based Analysis:** Uses packet-level inspection to provide additional verification context.
- **Accurate Results:** Aims to reduce false-positive detections and improve the reliability of scan results.
- **TCP/UDP Analysis:** Supports analysis of TCP and UDP port states.

The goal is to identify genuinely responsive services while minimizing misleading port detection results.

---

### 🔍 ADVANCED RECONNAISSANCE

### ⚡ INTELLIGENT DETECTION

### 📊 AUTOMATED REPORTING

---

# 📌 ABOUT THE PROJECT

**Nmap-TShark-Enhanced-Scanner** is an advanced network reconnaissance and security analysis framework that combines Nmap's scanning capabilities with Wireshark/TShark network traffic analysis.

Developed through an extensive period of development, experimentation, testing, and continuous improvement, this project focuses on enhancing port detection reliability and reducing false-positive results.

The framework combines active network scanning with packet-level traffic analysis to provide deeper visibility into discovered network services.

### 🌐 Bulk Domain & Subdomain Scanning

The scanner supports scanning multiple domains and subdomains through a simple text-based input system.

- Add one or multiple domains or subdomains to `domainler.txt`.
- Supports individual targets as well as large target lists.
- Automatically processes targets sequentially.
- No need to manually start a scan for each domain.

**Example `domainler.txt`:**

```text
example.com
www.example.com
api.example.com
mail.example.com
dev.example.com
test.example.com
```

Add your authorized target domains and subdomains to `domainler.txt`, save the file, and start the scanner:

```bash
nano domainler.txt
```

The scanner will automatically process the listed targets one by one.

### 🔄 Automatic Scan Recovery

The framework is designed to handle unexpected interruptions and resume scanning from the last saved progress.

- **Internet Disconnection:** Scanning pauses when the internet connection is lost and resumes when connectivity is restored.
- **Power Outage:** Saved progress allows scanning to continue after the computer restarts.
- **System Shutdown:** Previously completed progress is preserved.
- **Automatic Recovery:** Restarting the scanner allows it to continue from its saved progress instead of starting from the beginning.

The goal is to provide an integrated and practical reconnaissance environment for authorized security research, combining intelligent scanning, traffic analysis, bulk target processing, and automatic recovery mechanisms.

---

# 🚀 KEY FEATURES

<img width="100%" alt="Nmap-TShark Enhanced Scanner Output" src="https://github.com/user-attachments/assets/c8ab1623-4365-439f-b131-5bcc7f67940e" />

### 🔍 Advanced Port Detection

- TCP port scanning
- UDP port scanning
- Port state identification
- Response analysis
- Intelligent filtering
- False-positive reduction



### 📡 Network Traffic Analysis

- Wireshark integration
- TShark analysis
- Packet inspection
- PCAP analysis
- Protocol identification
- Traffic inspection

### 🔐 Proxy Support

The scanner includes optional proxy configuration, allowing users to enable or disable proxy usage through simple configuration settings.

- **Proxy Toggle:** Enable or disable proxy support using `USE_PROXY`.
- **Multiple Proxy Entries:** Configure multiple proxy servers in `PROXY_LIST`.
- **HTTP Proxy Support:** Supports HTTP proxy configurations.
- **SOCKS5 Proxy Support:** Supports SOCKS5 proxy configurations.
- **Flexible Configuration:** Easily customize proxy addresses and ports.

**Example Configuration:**

```python
USE_PROXY = False

PROXY_LIST = [
    "http://127.0.0.1:8080",
    "socks5://127.0.0.1:9050",
]
```

Set `USE_PROXY = True` to enable proxy usage, or leave it as `False` to disable it.


### 🧠 Intelligent Filtering

- Port result validation
- Response consistency analysis
- False-positive reduction mechanisms
- Scan result verification


### 🖥️ Service Identification

- Service detection
- Version identification
- HTTP/HTTPS inspection
- Server response analysis


### 🌐 Web Reconnaissance

- Web technology detection
- Server fingerprinting
- WAF detection indicators
- CDN detection indicators
- Endpoint discovery integration


### 📊 Automated Reporting

- HTML reports
- JSON results
- Scan summaries
- Progress monitoring
- Checkpoint management
- FTP report transfer


---

# ⚙️ TECHNOLOGY STACK

| Technology | Integration                    |
| ---------- | ------------------------------ |
| Python     | Main framework                 |
| Nmap       | Network scanning engine        |
| Wireshark  | Network traffic analysis       |
| TShark     | Packet inspection              |
| HTML       | Report generation              |
| JSON       | Result storage                 |
| XAMPP FTP  | Optional remote report storage |

---

# 🖥️ SUPPORTED PLATFORMS

| Operating System       | Support   |
| ---------------------- | --------- |
| Kali Linux             | Supported |
| Debian                 | Supported |
| Ubuntu                 | Supported |
| WSL2                   | Supported |
| Linux Virtual Machines | Supported |

---

<img width="50%" alt="Nmap-TShark Enhanced Scanner Output" src="https://github.com/user-attachments/assets/03af413d-1bbe-4a1e-93f2-652cee607e73">


# 📦 INSTALLATION

### 1. Update Your System

```bash
sudo apt update && sudo apt upgrade -y
```

### 2. Install Dependencies

```bash
sudo apt install -y \
python3 \
python3-pip \
python3-venv \
python3-dev \
nmap \
tshark \
wireshark \
git \
curl \
wget \
dnsutils
```

### 3. Clone Repository

```bash
git clone YOUR_REPOSITORY_URL
```

```bash
cd Nmap-TShark-Enhanced-Scanner-v1.0
```

### 4. Create Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate
```

### 5. Install Python Requirements

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 6. Verify Installation

```bash
python3 --version
nmap --version
tshark --version
```

---

# 🏗️ FRAMEWORK ARCHITECTURE

```text
          NMAP-TSHARK ENHANCED SCANNER
                       |
          +------------+------------+
          |                         |
     NMAP ENGINE              TSHARK ENGINE
          |                         |
    PORT DISCOVERY            PACKET ANALYSIS
          |                         |
          +------------+------------+
                       |
              INTELLIGENT FILTER
                       |
                RESULT ANALYSIS
                       |
          +------------+------------+
          |                         |
    SERVICE DETECTION         WEB ANALYSIS
          |                         |
          +------------+------------+
                       |
                REPORTING ENGINE
                       |
          +------------+------------+
          |                         |
       HTML REPORT              JSON OUTPUT
          |                         |
          +------------+------------+
                       |
                 STORAGE SYSTEM
                 /           \
              LOCAL          FTP
```

---

# 📊 REPORTING SYSTEM

The framework supports structured scan reporting and multiple storage options.

### Local Report Storage

Reports can be stored inside the `rapor/` directory.

```text
rapor/
│
├── report.html
├── scan_results.json
│
└── checkpoints/
```

### FTP Report Storage

Optional FTP integration allows generated HTML reports to be transferred to a configured FTP server.

Supported environment:

- XAMPP FTP Server
- Configured FTP storage

**Security:** FTP credentials must be stored securely and must never be committed to the public repository.

---

# 🖼️ SCREENSHOTS & DEMONSTRATIONS

Visual demonstrations will be added as the project documentation develops.

### Main Interface



### Port Detection Results



### Network Analysis



### HTML Reporting



---

# 🎯 DEVELOPMENT OBJECTIVES

- Improve port detection reliability.
- Reduce false-positive results.
- Combine network scanning with packet analysis.
- Improve service identification.
- Provide structured scan results.
- Simplify reconnaissance workflows.
- Generate professional reports.

---

# 👨‍💻 INTENDED AUDIENCE

- Cybersecurity Researchers
- Network Administrators
- Penetration Testers
- Authorized Bug Bounty Researchers
- Security Assessment Professionals
- Network Analysis Enthusiasts

---

# ⚖️ SECURITY & LEGAL DISCLAIMER

This project is intended exclusively for authorized security testing, educational purposes, network administration, and legitimate cybersecurity research.

Users must obtain appropriate authorization before scanning or analyzing any network, host, or infrastructure.

Unauthorized scanning, testing, or access may violate applicable laws, regulations, and service agreements.

The developer does not authorize malicious or unlawful use of this software.

Users are responsible for ensuring compliance with applicable laws.

---

# 📜 THIRD-PARTY SOFTWARE & LICENSING

This project utilizes third-party technologies:

- Nmap
- Wireshark
- TShark

These components remain subject to their respective licenses and copyright holders.

The original project code and independently developed components are separate from third-party software.

Users should review applicable licensing requirements before redistribution or commercial deployment.

---

# 🔐 COPYRIGHT & OWNERSHIP


### DEVELOPED BY

# ByRooT

**Nmap-TShark-Enhanced-Scanner**

Copyright © 2026 ByRooT


The original source code, independently developed filtering logic, project architecture, and custom components are attributed to ByRooT, subject to applicable third-party licenses.

Third-party software is not claimed as original work.

All rights to original project components are reserved by their respective copyright holder.

---

# 📈 PROJECT STATUS

| Information      | Details                      |
| ---------------- | ---------------------------- |
| Project          | Nmap-TShark-Enhanced-Scanner |
| Developer        | ByRooT                       |
| Version          | 1.0                          |
| Year             | 2026                         |
| Status           | Active Development           |
| Primary Language | Python                       |

---


# 🛡️ BYROOT

### ADVANCED RECONNAISSANCE

### INTELLIGENT DETECTION

### INTEGRATED NETWORK ANALYSIS

**Built for Security Research.**

