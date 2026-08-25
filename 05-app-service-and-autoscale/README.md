# Lab 05: Azure App Service, Deployment Slots, and Autoscaling

## 📌 Overview
This lab focuses on hosting web applications with high availability and automated scaling. It covers deploying an Azure App Service, utilizing deployment slots for zero-downtime deployment swaps, and establishing automated CPU autoscaling rules to handle traffic spikes[cite: 1].

---

## 🛠️ Built With & Technologies Used
* **Azure App Service Plan** (SKUs & Worker Allocation)[cite: 1]
* **Deployment Slots** (Staging & Production Environments)[cite: 1]
* **Azure Autoscaling Rules** (Metric-Based Scale-Out / Scale-In)[cite: 1]
* **GitHub Integration** (Continuous Deployment Pipeline)[cite: 1]

---

## 🎯 Key Implementation Steps

1. **App Service Provisioning:** Configured a production-tier App Service Plan and deployed a web application linked to a GitHub code repository[cite: 1].
2. **Staging Environment Setup:** Configured a dedicated `staging` deployment slot to test application updates isolated from production traffic[cite: 1].
3. **Zero-Downtime Slot Swap:** Executed a deployment slot swap between `staging` and `production`, verifying seamless configuration propagation without service disruption[cite: 1].
4. **Metric Autoscale Policy:** Created dynamic scale-out rules that automatically increase instance counts when CPU utilization exceeds threshold limits, and scale in during low-demand periods[cite: 1].

---

## 🖼️ Verification & Proof of Concept

*(Drop 2–3 screenshots here demonstrating a successful slot swap operation, App Service status, or autoscale metric configuration)*[cite: 1, 4]

- `![App Service Deployment Slots](./screenshots/deployment-slots.png)`
- `![Slot Swap Operation Complete](./screenshots/slot-swap.png)`
- `![Autoscale Rule Engine](./screenshots/autoscale-rules.png)`
