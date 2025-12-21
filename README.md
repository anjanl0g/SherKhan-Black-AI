# 💀 SherKhan Black AI (v5.0 - JARVIS Edition)

**The World's First Autonomous Offensive & Defensive AI Ecosystem.**
*Powered by Swarm Intelligence | Vision | Voice | Active Deception*

![Status](https://img.shields.io/badge/Status-Operational-brightgreen) ![Version](https://img.shields.io/badge/Version-5.0_JARVIS-red) ![Privacy](https://img.shields.io/badge/Privacy-100%25_Offline-blue) ![Role](https://img.shields.io/badge/Role-Red_&_Blue_Team-black)

## ⚡ System Overview
**SherKhan Black AI** is not a chatbot; it is a fully autonomous **Cyber Defense & Offense Agent**. Unlike standard LLMs (ChatGPT/Gemini) that only generate text, SherKhan **sees, hears, executes, and defends** in real-time.

It utilizes a **Swarm Intelligence Architecture**, coordinating multiple AI agents to scan targets, analyze threats, and generate reports, while simultaneously running a **Ghost Protocol (Honeypot)** to trap attackers.

---

## 📸 Interface Preview

### 😈 Hacker Mode (Offensive Ops)
*Powered by Dolphin-Mistral (Uncensored)*
![Hacker Mode](assets/1.png)

### 💻 Coder Mode (DevSecOps)
*Powered by Qwen-Coder (Secure Development)*
![Coder Mode](assets/2.png)

---

## 🚀 Key Features (v5.0)

### 1. 🐝 Swarm Intelligence (Multi-Agent System)
Instead of a single bot, SherKhan deploys a squad:
*   **Agent 1 (Hunter):** Scans the target and finds raw vulnerabilities.
*   **Agent 2 (Researcher):** Maps findings to CVEs and suggests technical fixes.
*   **Agent 3 (Writer):** Compiles a professional PDF Mission Report.

### 2. 🛡️ Ghost Protocol (Active Defense)
*   SherKhan doesn't just attack; it defends.
*   Runs a **Fake SSH Trap** on Port 2222.
*   **Capture:** Logs attacker IPs, usernames, and passwords directly to the internal database (`sherkhan.db`).
*   **Alert:** Notifies you instantly via the Dashboard.

### 3. 👁️ Vision Capabilities (The Eyes)
*   **Analyze Screenshots:** Upload images of login pages, logs, or code.
*   SherKhan uses **LLaVA** to detect phishing clones, UI errors, or hidden threats visually.

### 4. 📂 Deep File Analysis (PCAP & Logs)
*   **Packet Inspector:** Upload `.pcap` (Wireshark) files.
*   SherKhan analyzes network traffic, extracts unique IPs, and detects anomalies using Scapy + AI.

### 5. 🗣️ Voice Command Center (The Mouth)
*   **Talk to SherKhan:** Full Two-Way Audio communication.
*   Give commands like *"Scan localhost"* or *"Analyze this file"* via microphone.

### 6. ⚡ Real-Time Tool Execution
Directly controls Kali Linux arsenal:
*   `Nmap` (Network Discovery)
*   `Nikto` (Web Vulnerability)
*   `Gobuster` (Directory Brute-force)
*   `Hydra` (Password Cracking)
*   `Sherlock` (OSINT Identity Tracking)

---

## 🛠️ Installation & Setup

### Option 1: Kali Linux / Ubuntu (Recommended)

**1. Initialize AI Models**
```bash
ollama pull dolphin-mistral  # The Hacker
ollama pull qwen2.5-coder    # The Coder
ollama pull mistral          # The Writer
ollama pull llava            # The Eyes
```

**2. Backend Setup**
```bash
cd pentest_backend
pip install -r requirements.txt
python main.py
```

**3. Frontend Setup**
```bash
cd pentest_ui
npm install
npm run dev
```

---

### Option 2: 🪟 Windows Installation

**Prerequisites:**
*   [Python 3.10+](https://www.python.org/downloads/)
*   [Node.js (LTS)](https://nodejs.org/)
*   [Ollama for Windows](https://ollama.com/download/windows)
*   [Npcap](https://npcap.com/) (Required for Scapy/Wireshark features)

**1. Setup AI Models (PowerShell)**
Open PowerShell and run:
```powershell
ollama pull dolphin-mistral
ollama pull qwen2.5-coder
ollama pull llava
```

**2. Backend Setup**
```powershell
cd pentest_backend
pip install -r requirements.txt
python main.py
```
*Note: If you get a "command not found" error for tools like Nmap, ensure you have installed the Windows versions of Nmap, Nikto, etc., and added them to your System PATH.*

**3. Frontend Setup**
Open a new PowerShell window:
```powershell
cd pentest_ui
npm install
npm run dev
```
*Access Dashboard at: `http://localhost:3000`*

---

## 👨‍💻 About the Author

**Sher Khan**
*Lead Cyber Security Architect & AI Developer*

The creator of **SherKhan Black AI**, dedicated to advancing the field of **Autonomous Cyber Warfare** and **DevSecOps**. This project represents the fusion of Offensive Security and Generative AI.

*   **GitHub:** [anjanl0g](https://github.com/anjanl0g)
*   **LinkedIn:** [Sher Khan](https://www.linkedin.com/in/sherkhan-sk/)
*   **Mission:** Building the JARVIS for Cyber Security.

---

## ⚠️ Legal Disclaimer
**SherKhan Black AI is a Security Assessment Tool.**
It is designed for **Authorized Red Teaming** and **Educational Purposes** only.
*   Do not use this tool on networks you do not own or have permission to test.
*   The developers are not responsible for misuse.
