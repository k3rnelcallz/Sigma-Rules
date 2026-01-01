# Sigma-Rules

**Sigma rules for log detection** — a community-driven catalog of threat detection content in Sigma format, focused on real-world malware and suspicious behavior patterns.

This repository contains Sigma detection rules used to identify malicious activity and anomalies in log data, suitable for conversion to SIEM query languages (e.g., Elastic, Splunk, QRadar). :contentReference[oaicite:0]{index=0}

---

## 📌 What Is Sigma?

Sigma is an open, vendor-agnostic signature format for describing log events and detection logic. It lets security teams write detection rules once and then convert them to specific SIEM query languages. :contentReference[oaicite:1]{index=1}

Think of Sigma like **YARA for logs** — structured, sharable, and SIEM-agnostic.

---

## 📁 Repository Structure

| Folder / File | Description |
|---------------|-------------|
| `*.yml` | Individual Sigma rules covering suspicious behaviors |
| `README.md` | This documentation |
| Upcoming folders | (e.g., `windows/`, `linux/`, `attack_tactics/`) — for future rule classification |

Each rule includes metadata, detection logic, tags, and mappings to MITRE ATT&CK where appropriate.

---

## 🚀 How to Use the Rules

1. **Clone this repository**

   ```bash
   git clone https://github.com/k3rnelcallz/Sigma-Rules.git
