# SIEM-Analysis
SIEM scenarios and use cases for log analysis with Splunk and QRadar
# SIEM Log Analysis - Splunk & QRadar

## 📌 Project Description
This repository contains sample scenarios and queries for SIEM (Security Information and Event Management) analysis using **Splunk** and **IBM QRadar**. It is designed to demonstrate practical examples of log analysis, threat detection, and incident response.

## 🛠 Tools Used
- **Splunk**: For real-time search, analysis, and visualization of machine-generated data.
- **IBM QRadar**: For centralized log management and correlation rules.

## 📁 Structure
```
SIEM-Analysis/
├── splunk/
│   ├── failed_logins.md
│   ├── brute_force_detection.md
│   └── suspicious_processes.md
├── qradar/
│   ├── firewall_rule_trigger.md
│   ├── dns_tunneling.md
│   └── abnormal_login_pattern.md
└── README.md
```

## 🔍 Sample Use Cases
### Splunk
- Detecting multiple failed login attempts from the same IP
- Correlating PowerShell process usage with admin accounts

### QRadar
- Custom rule for DNS tunneling detection
- Alerting on logins from different geolocations within short time intervals

## 📈 Purpose
The goal of this repository is to help:
- SOC analysts understand real-world detection logic
- Beginners explore the syntax and structure of SIEM rules
- Anyone build a personal SOC lab

## 🤝 Contributions
Feel free to fork this repository and contribute with new use cases, improved queries, or other SIEM platforms like ArcSight or Sentinel.

## 📬 Contact
For suggestions or questions, feel free to reach out via GitHub or open an issue.

---
🔐 *Stay alert. Log everything. Trust nothing.*
