# Lab 01: Virtual Machines, Custom RBAC, and Cost Governance

## 📌 Overview
This lab covers deploying virtual machine infrastructure in Microsoft Azure, establishing administrative boundaries using custom Role-Based Access Control (RBAC), enforcing organization-wide tagging standards via Azure Policy, and configuring financial budget alerts.

---

## 🛠️ Built With & Technologies Used
* **Azure Virtual Machines** (Compute & Disk Encryption)
* **Microsoft Entra ID** (Custom RBAC Roles & Permissions)
* **Azure Policy** (Mandatory Resource Tagging Enforcement)
* **Azure Cost Management** (Budget Alerts & Spend Thresholds)

---

## 🎯 Key Implementation Steps

1. **Virtual Machine Deployment:** Provisioned a standard VM size with OS Disk Encryption enabled to enforce security and compliance baseline standards.
2. **Azure Policy Assignment:** Created and assigned an Azure Policy requiring a mandatory `Department` tag on all resources created inside the resource group.
3. **Least-Privilege RBAC Configuration:** Configured a custom Entra ID role providing minimum necessary rights to restart and inspect the VM without granting broad contributor permissions.
4. **Cost Governance:** Built an automated budget threshold alert in Azure Cost Management to send email notifications when spending hits designated limits.

---

## 🖼️ Verification & Proof of Concept

*(Drop 2–3 screenshots here showing your VM, Policy compliance, or custom RBAC assignment)*

- `![Custom RBAC Role](./screenshots/rbac-role.png)`
- `![Policy Compliance](./screenshots/policy-compliance.png)`
