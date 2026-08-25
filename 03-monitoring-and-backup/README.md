# Lab 03: Operational Monitoring, KQL Diagnostics, and VM Recovery

## 📌 Overview
This lab focuses on establishing operational visibility and data protection across Azure infrastructure. It covers configuring metric and log-based alerts in Azure Monitor, querying telemetry with Kusto Query Language (KQL) in Log Analytics, and setting up disaster recovery backup policies with an Azure Recovery Services Vault[cite: 1].

---

## 🛠️ Built With & Technologies Used
* **Azure Monitor** (Metric Alerts & Action Groups)[cite: 1]
* **Log Analytics Workspace** (Diagnostic Settings & KQL)[cite: 1]
* **Kusto Query Language (KQL)** (Log Telemetry Analysis)[cite: 1]
* **Recovery Services Vault** (Azure Backup & Restore Points)[cite: 1]

---

## 🎯 Key Implementation Steps

1. **Log Analytics Configuration:** Deployed a central Log Analytics Workspace and connected virtual machine diagnostic settings to collect system operational logs[cite: 1].
2. **KQL Querying:** Authored custom Kusto Query Language (KQL) scripts to filter and surface specific operational signals and event logs from collected telemetry[cite: 1].
3. **Alert Rule Engine:** Configured both metric alerts (CPU usage thresholds) and log alerts (query-matched log events) with action notifications[cite: 1].
4. **Backup & Recovery Strategy:** Configured a Recovery Services Vault, defined a daily backup retention policy, initiated an on-demand backup, and verified restore point availability[cite: 1].

---

## 🖼️ Verification & Proof of Concept

*(Drop 2–3 screenshots here demonstrating KQL query results, active alert rules, or completed backup restore points)*[cite: 1, 4]

- `![KQL Query Results](./screenshots/kql-query.png)`
- `![Azure Monitor Alert](./screenshots/azure-monitor-alert.png)`
- `![Recovery Services Vault Backup](./screenshots/backup-restore-point.png)`
