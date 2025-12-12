# 💀 Sher Khan Black A.I (Omni-Layer)

![Status](https://img.shields.io/badge/Status-Operational-brightgreen) ![Version](https://img.shields.io/badge/Version-2.0-red) ![Engine](https://img.shields.io/badge/Engine-Hybrid%20LLM-blue)

**The Ultimate Autonomous Cyber Warfare Suite.**
*Powered by Dolphin-Mistral (Uncensored) & Qwen-Coder (Dev).*

## 📖 Introduction
**Sher Khan Black A.I** is an advanced, agentic cybersecurity framework designed for Red, Blue, and Black team operations. Unlike standard chatbots, this tool possesses **Real-Time Execution Capabilities**. It routes commands through a smart backend to either execute native Kali Linux tools (Nmap, Hydra, Nikto) or generate advanced payloads using local AI models.

It operates on a **Dual-Core Hybrid Engine**:
*   😈 **Hacker Mode (Red Skull):** Uses `dolphin-mistral` for uncensored operations, exploit generation, and social engineering.
*   💻 **Coder Mode (Blue Laptop):** Uses `qwen2.5-coder` for precise scripting, debugging, and log analysis.

---

## ⚙️ Prerequisites (System Setup)
Before running the tool, ensure you have the following installed on your Kali Linux/Ubuntu system:
*   **Python 3.8+**
*   **Node.js & npm** (v18 or higher)
*   **Ollama** (for running local AI models)
*   **Kali Tools:** `nmap`, `nikto`, `hydra`, `sherlock`, `macchanger`

### 🧠 Step 0: Install AI Brains
Open a terminal and run these commands to download the required AI models:

```bash
# Uncensored Model for Black Hat Ops
ollama pull dolphin-mistral

# Coding Model for Scripting & Analysis
ollama pull qwen2.5-coder
```

---

## 🚀 Deployment Guide (How to Run)

To run the full suite, you need to open **2 Separate Terminals**. Follow the exact order below:

### 🐍 Terminal 1: The Backend Engine
This terminal runs the Python API that connects to Kali Linux tools and the AI models.

1.  Navigate to the backend folder:
    ```bash
    cd pentest_backend
    ```
2.  Create and activate virtual environment (First time only):
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```
3.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4.  **Start the Server:**
    ```bash
    python3 -m uvicorn main:app --reload
    ```
    > ✅ *Success Message: "Application startup complete. Running on http://127.0.0.1:8000"*

---

### ⚛️ Terminal 2: The Frontend Dashboard
This terminal runs the professional React/Next.js User Interface.

1.  Navigate to the UI folder:
    ```bash
    cd pentest-ui
    ```
2.  Install Node modules (First time only):
    ```bash
    npm install
    ```
3.  **Start the Dashboard:**
    ```bash
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

> *This tool is developed for educational purposes and authorized penetration testing only. The author is not responsible for any misuse. Always obtain written permission before scanning any target.*
```
