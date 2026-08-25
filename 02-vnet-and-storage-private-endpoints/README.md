# Lab 02: Virtual Networks, Network Security Groups, and Storage Private Endpoints

## 📌 Overview
This lab focuses on configuring secure virtual network boundaries in Microsoft Azure, restricting traffic using Network Security Groups (NSGs), securing an Azure Storage Account by disabling public endpoint access, and implementing a Private Endpoint to allow secure access exclusively through a Virtual Network (VNet)[cite: 1].

---

## 🛠️ Built With & Technologies Used
* **Azure Virtual Network (VNet)** (Subnets & Address Spaces)[cite: 1]
* **Network Security Groups (NSGs)** (Inbound & Outbound Security Rules)[cite: 1]
* **Azure Storage Account** (Blob Storage & Private Endpoint Integration)[cite: 1]
* **Private Link / Private Endpoint** (Internal IP Access)[cite: 1]
* **Azure Bicep / ARM Templates** (Infrastructure as Code Automation)[cite: 1]

---

## 🎯 Key Implementation Steps

1. **Virtual Network & Subnet Topology:** Provisioned a custom VNet configured with dedicated subnets for compute workload resources and private endpoints[cite: 1].
2. **Network Security Group (NSG) Configuration:** Applied granular inbound and outbound security rules to enforce explicit traffic flow limits[cite: 1].
3. **Storage Hardening:** Deployed an Azure Storage Account with all public network access fully disabled to prevent unauthorized internet exposure[cite: 1].
4. **Private Endpoint Integration:** Attached a Private Endpoint to the storage account, assigning it a private IP address within the local VNet subnet[cite: 1].
5. **Infrastructure as Code (IaC):** Exported and documented the deployment as an Azure Bicep/ARM template for repeatable infrastructure provisioning[cite: 1].

---

## 🖼️ Verification & Proof of Concept

*(Drop 2–3 screenshots here demonstrating your Private Endpoint configuration, NSG rules, or blocked public access attempt)*

- `![NSG Rules Setup](./screenshots/nsg-rules.png)`
- `![Private Endpoint Connection](./screenshots/private-endpoint.png)`
- `![Disabled Public Access Verification](./screenshots/storage-access-blocked.png)`
