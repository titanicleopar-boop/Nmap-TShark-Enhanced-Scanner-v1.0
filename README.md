\<div align="center">

# 🛡️ NMAP-TSHARK ENHANCED SCANNER

### ADVANCED NETWORK RECONNAISSANCE FRAMEWORK

**Developed by ByRooT**

\

<img width="100%" alt="Nmap-TShark Enhanced Scanner Output" src="https://github.com/user-attachments/assets/03af413d-1bbe-4a1e-93f2-652cee607e73">



\


**Intelligent Port Detection | Traffic Analysis | False-Positive Filtering**

---

### 🔍 ADVANCED RECONNAISSANCE

### ⚡ INTELLIGENT DETECTION

### 📊 AUTOMATED REPORTING

\</div>

---

# 📌 ABOUT THE PROJECT

**Nmap-TShark-Enhanced-Scanner** is an advanced network reconnaissance and security analysis framework combining Nmap scanning capabilities with Wireshark/TShark network traffic analysis.

Developed through months of experimentation, testing, and continuous improvements, this project focuses on improving port detection reliability and reducing misleading scan results.

The framework combines active network scanning with packet-level traffic analysis to provide additional visibility into discovered network services.

The goal is to deliver an integrated and practical reconnaissance environment for authorized security research.

---

# 🚀 KEY FEATURES

\<table>
\<tr>
\<td width="50%">

### 🔍 Advanced Port Detection

- TCP port scanning
- UDP port scanning
- Port state identification
- Response analysis
- Intelligent filtering
- False-positive reduction

\</td>
\<td width="50%">

### 📡 Network Traffic Analysis

- Wireshark integration
- TShark analysis
- Packet inspection
- PCAP analysis
- Protocol identification
- Traffic inspection

\</td>
\</tr>

\<tr>
\<td width="50%">

### 🧠 Intelligent Filtering

- Port result validation
- Response consistency analysis
- False-positive reduction mechanisms
- Scan result verification

\</td>
\<td width="50%">

### 🖥️ Service Identification

- Service detection
- Version identification
- HTTP/HTTPS inspection
- Server response analysis

\</td>
\</tr>

\<tr>
\<td width="50%">

### 🌐 Web Reconnaissance

- Web technology detection
- Server fingerprinting
- WAF detection indicators
- CDN detection indicators
- Endpoint discovery integration

\</td>
\<td width="50%">

### 📊 Automated Reporting

- HTML reports
- JSON results
- Scan summaries
- Progress monitoring
- Checkpoint management
- FTP report transfer

\</td> \</tr> \</table>

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

\<div align="center">

### DEVELOPED BY

# ByRooT

**Nmap-TShark-Enhanced-Scanner**

Copyright © 2026 ByRooT

\</div>

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

\<div align="center">

# 🛡️ BYROOT

### ADVANCED RECONNAISSANCE

### INTELLIGENT DETECTION

### INTEGRATED NETWORK ANALYSIS

**Built for Security Research.**

\</div>
