# Industrial-SOC-Implementation-Using-Wazuh-ELK
Design and Implementation of an Industrial-Grade Security Operations Center (SOC) using Wazuh and ELK Stack


# 🔐 Industrial-Grade Security Operations Center (SOC) using Wazuh & ELK Stack

## 📌 Project Overview

This project demonstrates the **design and implementation of an Industrial-Grade Security Operations Center (SOC)** using integrated open-source SIEM technologies.

The solution provides centralized log monitoring, real-time threat detection, file integrity monitoring, malware analysis, and automated incident response using a virtual lab environment.

The SOC architecture integrates:

- Wazuh (SIEM & Host-based Intrusion Detection)
- Elasticsearch (Data Indexing & Search Engine)
- Kibana (Visualization & Dashboard)
- Filebeat (Log Forwarding)
- VirusTotal API (Threat Intelligence Integration)
- VirtualBox Lab Environment

This implementation provides a cost-effective and scalable cybersecurity monitoring framework suitable for mid-level industries and academic environments.

---
## 🎯 Objectives

- Build a fully functional SOC using open-source tools
- Implement real-time log monitoring and threat detection
- Integrate malware intelligence using VirusTotal API
- Demonstrate Active Response automation
- Compare traditional ELK pipeline vs Wazuh-integrated SIEM architecture

---

## 🏗️ System Architecture

### 🔹 Infrastructure Overview

Agents (Windows & Ubuntu) →  
Wazuh Manager →  
Filebeat →  
Elasticsearch →  
Kibana Dashboard  

Additionally:
Wazuh ↔ VirusTotal API for malware hash verification

---


## 🚀 Key Features Implemented

### 1️⃣ Centralized Log Collection
- Collects logs from multiple agents
- Stores and analyzes logs at Wazuh Manager

### 2️⃣ File Integrity Monitoring (FIM)
- Detects unauthorized file modifications
- Tracks file hash changes (SHA256)
- Alerts triggered for suspicious activity

### 3️⃣ Malware Detection Integration
- Integrated VirusTotal API
- Automated hash verification
- Dashboard alerts for infected files

### 4️⃣ Active Response Mechanism
- Automatic IP blocking after repeated failed login attempts
- Brute-force attack mitigation
- Temporary user blocking policy
- Incident logging and alerting

### 5️⃣ Threat Intelligence Workflow
- Real-time file hash scanning
- Automated malware classification
- Visual threat reporting in Kibana

### 6️⃣ SSL Configuration
- Secure communication between services
- Encrypted dashboard access

---


## 📈 Results

- Real-time log monitoring achieved
- Malware detection automated
- Brute-force attack successfully mitigated
- File modification events tracked
- Threat visualization via Kibana dashboard

---

## 🛠️ Technologies Used

- Wazuh
- Elasticsearch
- Kibana
- Filebeat
- VirusTotal API
- VirtualBox
- Kali Linux
- Ubuntu
- Windows XP

---

## 🔐 Security Capabilities Demonstrated

- Host-based Intrusion Detection (HIDS)
- Log Correlation
- File Integrity Monitoring
- Threat Intelligence Integration
- Incident Response Automation
- Brute-force Detection
- Basic DDoS Detection Logic
- SSL-secured Dashboard Access
