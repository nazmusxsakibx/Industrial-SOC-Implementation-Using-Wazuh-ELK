# Industrial-SOC-Implementation-Using-Wazuh-ELK
Design and Implementation of an Industrial-Grade Security Operations Center (SOC) using Wazuh and ELK Stack

# 🔐 Industrial-Grade Security Operations Center (SOC)

# 📌 Project Overview

This project demonstrates the design and implementation of an Industrial-Grade Security Operations Center (SOC) using open-source SIEM technologies.

# The system integrates:

Wazuh (SIEM + HIDS)
Elasticsearch (Data Indexing)
Kibana (Dashboard & Visualization)
VirusTotal (Threat Intelligence API)
VirtualBox Lab Environment

# The solution provides:

✔ Log Monitoring
✔ File Integrity Monitoring
✔ Malware Detection
✔ Active Response
✔ Intrusion Detection
✔ Brute-force Detection
✔ Automated Threat Response

# 🔍 Features Implemented

1️⃣ Log Collection: Wazuh Manager collects logs from multiple agents.

2️⃣ File Integrity Monitoring: Detects unauthorized file modifications using SHA256 hashing.

3️⃣ Malware Detection: Integrated VirusTotal API for automated malware hash verification.

4️⃣ Active Response: 
Blocks attacker IP after multiple failed login attempts.
Prevents brute-force attack.
Temporary IP banning.

5️⃣ Threat Intelligence Integration: Automated malware detection workflow using VirusTotal.
