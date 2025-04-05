/# 🔐 Centralized Application-Context Aware Firewall (AI-Powered)

> A Smart Cybersecurity Solution by Team **KERNEL PANIC – WireNet | Next Quantum 2.0**

This repository presents an innovative solution for modern cybersecurity challenges — a **Centralized Application-Context Aware Firewall** that uses **AI/ML-based anomaly detection**, context-aware network monitoring, and centralized policy enforcement through a unified dashboard.

---

## 📌 Problem Statement

Traditional firewalls are often generic, lack contextual intelligence, and are difficult to manage across distributed systems. They fail to provide app-specific control and often miss early signs of anomalies in application behavior.

---

## 🎯 Our Proposed Solution---

An **AI-powered firewall agent** installed on endpoint systems that:
- Monitors application-specific network activities
- Detects suspicious behaviors in real-time using AI
- Enforces security policies from a centralized dashboard
- Alerts the cybersecurity team when an anomaly is detected

This allows for:
- 🔄 Context-aware threat detection
- 📶 Real-time network monitoring
- 🔧 Centralized rule-based enforcement
- 📊 Unified visualization of endpoint activity

---

## 🌟 Key Features

### ✅ App-Wise Network Access Control
Each application's network behavior is individually tracked and controlled.

### 🤖 AI/ML-Based Anomaly Detection
Advanced ML models (e.g., Isolation Forest) are used to detect deviations from normal activity.

### 🧠 Context-Awareness
The firewall understands **what app** is doing **what**, **when**, and **why** — improving detection accuracy.

### 🛠 Centralized Dashboard
All monitoring, policy enforcement, and log analytics are done from a single web interface.

### 📄 Detailed Logs
All application network events are logged, analyzed, and made available for export or review.

### 🌐 Cross-Platform Compatibility
Designed for Windows initially, easily adaptable for Linux-based systems.

### 🔐 Stronger Endpoint Security
Users and administrators can take full control of endpoint traffic using fine-grained, automated rules.

---

## ⚙️ Technical Architecture

### 🧱 Tech Stack

| Component         | Technology Used        | Purpose |
|------------------|------------------------|---------|
| Frontend         | HTML5, CSS3, JavaScript | Interactive UI & dashboard  
| Backend (API)    | Python (Flask)          | REST API, data processing, ML integration  
| ML Models        | Isolation Forest        | Anomaly detection from logs  
| Data Storage     | SQLite / MongoDB        | Log and policy persistence  
| Agent Software   | Python (lightweight)    | Deployed on endpoint machines  
| Communication    | Secure HTTP (REST)      | Data transmission from agents to server  

---

## 🛠️ Functional Methodology

1. **Agent Installation:**  
   Lightweight Python-based firewall agents are installed on endpoints.

2. **Real-Time Monitoring:**  
   Each agent tracks:
   - IP addresses and ports
   - Protocol types
   - App-wise traffic volume
   - Time and frequency of access

3. **Centralized Policy Enforcement:**  
   Admins configure allow/deny rules on a central server. Agents fetch these rules periodically.

4. **Data Logging:**  
   Agents transmit activity logs to the central Flask server using secure REST APIs.

5. **AI/ML Detection:**  
   An Isolation Forest model processes logs to detect outliers, signaling potential threats.

6. **Dashboard Visualization:**  
   Admins access a web dashboard to:
   - View live traffic summaries
   - Inspect flagged anomalies
   - Modify policies in real-time

7. **Alerting System:**  
   If an anomaly is detected:
   - Admins receive a UI alert
   - Logs are saved for analysis
   - Future communication from the flagged app can be blocked automatically

---

## 📈 Impact

### 💻 Enhanced Security Posture
Gives cybersecurity teams a **context-aware**, fine-grained control over apps and data flows.

### ⚡ Improved Threat Response
AI-driven detection enables quicker action to emerging threats — before damage is done.

### 🧰 Reduced Management Overhead
Policies managed **centrally** eliminate manual configurations on each system.

### 🌱 Sustainable Computing
Efficient resource usage avoids unnecessary CPU/network load, reducing energy consumption.

---

## 🏛 Role of Governments & Compliance

This firewall system is aligned with:
- 🔐 **GDPR** – Ensures user data confidentiality
- 📜 **ISO 27001** – Supports ISMS implementation
- 🛡 **National Cybersecurity Policies** – Provides data visibility and endpoint integrity

Government and enterprise adoption of such systems can:
- Boost national cybersecurity infrastructure
- Enforce compliance across industries
- Promote local innovation in security tech

---

## 🧪 Feasibility Analysis

| Parameter              | Status |
|------------------------|--------|
| ✅ Technical           | Uses proven tech — Flask, Python, ML  
| ✅ Operational         | Lightweight agents, minimal setup  
| ✅ Economic            | Open-source base, scalable, cost-effective  
| ✅ Scalability         | Works across multiple systems and networks  
| ✅ Risk Management     | Encrypted communication, anomaly filtering  

### Potential Challenges & Mitigation

| Challenge               | Solution |
|------------------------|----------|
| Performance Overhead   | Agent is optimized for low CPU usage  
| False Positives        | Continuous model training & feedback loop  
| Security Breaches      | Token-based auth and HTTPS  
| Privacy Concerns       | Logs anonymized; audit-ready logs  

---

## 📂 File Structure

centralized-firewall/ ├── agent/ │ └── agent_firewall.py # Endpoint agent script ├── server/ │ ├── app.py # Flask backend │ ├── models.py # AI model & anomaly detection │ └── database.db # Policy/log storage (SQLite) ├── dashboard/ │ └── templates/ # HTML/CSS/JS frontend ├── datasets/ │ └── labeled_logs.csv # Labeled dataset for ML ├── README.md └── requirements.txt

yaml
Copy
Edit

---

## 💻 Getting Started

### ⚙️ Step 1: Install Requirements

```bash
pip install flask pandas sklearn plotly dash
🧪 Step 2: Start the Flask Server
bash
Copy
Edit
cd server
python app.py
🖥 Step 3: Run the Firewall Agent on Endpoint
bash
Copy
Edit
cd agent
python agent_firewall.py
🌐 Step 4: Access the Dashboard
Open in browser:

arduino
Copy
Edit
http://localhost:5000/
🧠 Future Scope
🔁 Integrate with real-time adb logs from connected Android devices

☁️ Host the dashboard on cloud (Heroku, AWS)

🔐 Add user authentication to dashboard

📩 Email & SMS alert system

🧠 Self-learning models using deep learning (autoencoders)

👨‍💻 Authors
Devashish Sharma – B.Tech CSE (8th Sem)

Aman Kumar – B.Tech CSE (4th Sem)

Abhishek – B.Tech CSE (4th Sem)

Gaurav Sehgal – B.Tech CSE (4th Sem)

❤️ Special Thanks
Thanks to Sant Baba Bhag Singh University and our mentors for guidance.

📬 Contact
📧 devashishsharma5000@gmail.com
📍 India

