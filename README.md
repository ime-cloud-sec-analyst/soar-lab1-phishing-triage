# soar-lab1-phishing-triage
This repo contains Lab 1: Build &amp; Test a SOAR Playbook for Phishing Triage.
# 🛡️ SOAR Lab 1: Phishing Triage Playbook

This repository contains the configuration and summary for **Lab 1: Build & Test a SOAR Playbook for Phishing Triage**.

## 📚 Lab Overview

The goal of this lab is to simulate a basic **Security Orchestration, Automation, and Response (SOAR)** process by building a playbook that:

- Receives suspicious phishing emails via a webhook
- Extracts relevant data (sender, subject, body)
- Uses AI or HTTP requests to assess threat context
- Sends alert emails to analysts
- Logs or transforms the data for reporting

## 🛠️ Tools Used

- **Tines (Free Plan)**
- **Webhook & HTTP Request Actions**
- **AI & Event Transform Actions**

## 🧩 Playbook Flow

1. **Webhook** – Receives suspicious emails
2. **Event Transform** – Extracts and cleans fields
3. **AI** – Evaluates intent or risk
4. **HTTP Request** – Sends results to a security tool (or simulated endpoint)
5. **(Optional)** Send email alerts

## 📂 Files

- `SOAR_Lab1_Phishing_Triage_Playbook_Completion_Report.docx` – Full lab report with screenshots and descriptions
- `README.md` – This documentation

## 👨‍💻 Author

**Ime Ben**  
Cloud & Security Analyst  
GitHub: [@ime-cloud-sec-analyst](https://github.com/ime-cloud-sec-analyst)

---

