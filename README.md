# 🛡️ PhishFree — Real-Time AI/ML-Based Phishing Detection

PhishFree is a **real-time phishing detection and prevention system** built for the **Smart India Hackathon (SIH)**. It integrates multi-modal AI analysis (Text, Vision, Graph) to protect users from phishing websites in real-time.

---

## 🚀 Features

- 🤖 **Multi-Modal AI Engine**:
  - **Text (RoBERTa)**: Analyzes page sentiment and intent.
  - **Vision (CNN)**: Detects brand impersonation and visual spoofing.
  - **Graph (GNN)**: Identifies malicious network patterns and domain clusters.
- 📸 **Automated Visual Evidence**: Captures and stores screenshots of analyzed pages for visual verification.
- 🌐 **URL Intelligence**: Real-time WHOIS, SSL, ASN, and DNS heuristic analysis.
- 📊 **Dynamic Dashboard**: Comprehensive view of all checks, analytics, and risk distributions.
- ⛓️ **Blockchain Integrity**: Analysis logs are anchored to the Ethereum (Sepolia) testnet for tamper-proof auditing.
- 🧩 **Smart Browser Extension**: Real-time alerts and explainable risk scores as you browse.

---

## 🛠️ Tech Stack

| Layer | Technologies |
|:------|:--------------|
| **Backend** | Python (Flask), Transformers, PyTorch, PyG, Web3.py |
| **Vision** | CNN/CLIP for visual similarity analysis |
| **Frontend** | Vanilla JS, CSS3, Chart.js (Dashboard) |
| **Extension** | Chrome Manifest V3 |
| **Database/Logs** | CSV-based decentralized logging with Blockchain anchoring |

---

## ⚙️ Installation

### 🧩 Step 1 — Clone the Repository
```bash
git clone https://github.com/Sahil-Scripts/Phish-Free.git
cd Phish-Free
```

### 🧱 Step 2 — Create Virtual Environment
```bash
python -m venv venv
# Activate
venv\Scripts\activate        # Windows
source venv/bin/activate     # Linux / Mac
```

### 📦 Step 3 — Install Dependencies
```bash
pip install -r backend/requirements.txt
```

---

## 🚀 Running the Project

1. **Start Backend**:
   ```bash
   cd backend
   python app.py
   ```
2. **Access Dashboard**: Open `http://localhost:5000/static/dashboard.html`
3. **Load Extension**:
   - Go to `chrome://extensions/`
   - Enable "Developer mode"
   - Click "Load unpacked" and select the `extension/` folder.

---

## ✨ Credits
Developed by **Team Vyuhatech** for **Smart India Hackathon (SIH)**.
