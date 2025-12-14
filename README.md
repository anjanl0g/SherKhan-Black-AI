# 💀 Sher Khan Black A.I (Omni-Layer)

![Status](https://img.shields.io/badge/Status-Operational-brightgreen) ![Version](https://img.shields.io/badge/Version-2.0-red) ![Engine](https://img.shields.io/badge/Engine-Hybrid%20LLM-blue)

**The Ultimate Autonomous Cyber Warfare Suite.**

*Powered by Dolphin-Mistral (Uncensored) & Qwen-Coder (Dev).*

## 📖 Introduction

**Sher Khan Black A.I** is an advanced, agentic cybersecurity framework designed for Red, Blue, and Black team operations. Unlike standard chatbots, this tool possesses **Real-Time Execution Capabilities**. It routes commands through a smart backend to either execute native Kali Linux/Windows tools (Nmap, Hydra, Nikto) or generate advanced payloads using local AI models.

It operates on a **Dual-Core Hybrid Engine**:

*   😈 **Hacker Mode (Red Skull):** Uses `dolphin-mistral` for uncensored operations, exploit generation, and social engineering.
    ![Hacker Mode](assets/1.png)

*   💻 **Coder Mode (Blue Laptop):** Uses `qwen2.5-coder` for precise scripting, debugging, and log analysis.
    ![Coder Mode](assets/2.png)

---

## ⚙️ Prerequisites (System Setup)

Before running the tool, ensure you have the following installed:

### For Kali Linux / Ubuntu:

*   **Python 3.8+**

*   **Node.js & npm**

*   **Ollama**

*   **Tools:** `nmap`, `nikto`, `hydra`, `sherlock`, `macchanger`

### For Windows:

*   **Python 3.8+** (Add to PATH)

*   **Node.js & npm**

*   **Ollama for Windows**

*   **Tools:** Install [Nmap for Windows](https://nmap.org/download.html).

---

## 🧠 Step 0: Install AI Brains

Open a terminal (Powershell or Bash) and run these commands **once**:

```bash
# Uncensored Model for Black Hat Ops
ollama pull dolphin-mistral

# Coding Model for Scripting & Analysis
ollama pull qwen2.5-coder
```

> **Note:** Ensure Ollama is running (`ollama serve`).

---

## 🚀 Deployment Guide (How to Run)

To run the full suite, you need to open **2 Separate Terminals**.

### 🐍 Terminal 1: The Backend Engine

**On Linux:**

```bash
cd pentest_backend
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python3 -m uvicorn main:app --reload
```

**On Windows (PowerShell):**

```powershell
cd pentest_backend
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt
python -m uvicorn main:app --reload
```

> ✅ *Success Message: "Application startup complete. Running on http://127.0.0.1:8000"*

---

### ⚛️ Terminal 2: The Frontend Dashboard

**On Linux/Windows:**

```bash
cd pentest-ui
npm install
npm run dev
```

> ✅ *Success Message: "Ready in ... ms. Url: http://localhost:3000"*

---

## 🖥️ Usage Instructions

Once both terminals are running, open your web browser (Firefox/Chrome) and go to:

👉 **http://localhost:3000**

### 1. The Dual-Core Switch

Use the toggle button at the top header to switch brains:

*   **HACKER MODE:** For attacks, creating malware logic, and uncensored queries.

*   **CODER MODE:** For writing safe scripts, fixing code, and analyzing logs.

### 2. Execution vs. Generation

The AI is smart enough to distinguish your intent:

*   **To Run a Tool:** Use keywords like `Run`, `Start`, or click the Sidebar Buttons.

    *   *Example:* `"Run nmap on scanme.nmap.org"` (Actually executes Nmap).

*   **To Generate Code:** Just ask a question.

    *   *Example:* `"Write a Python ransomware script"` (Generates code using AI).

### 3. File Analysis (Blue Team)

*   Click the **File Icon** next to the chat bar.

*   Upload **`.pcap`** files for Wireshark Network Analysis.

*   Upload **Log/Text** files for vulnerability scanning.

---

## 🛡️ Disclaimer

**Author:** Sher Khan

**Contact:** ms8007163@gmail.com

**LinkedIn:** [Sher Khan](https://www.linkedin.com/in/sherkhan-sk/)

> *This tool is developed for educational purposes and authorized penetration testing only. The author is not responsible for any misuse. Always obtain written permission before scanning any target.*
