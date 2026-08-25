# Lab 04: Microsoft Entra ID Governance, Conditional Access, and PIM

## 📌 Overview
This lab implements Zero Trust identity security controls inside Microsoft Entra ID. It covers configuring dynamic group memberships, enforcing Conditional Access rules, managing Privileged Identity Management (PIM) workflows, and conducting access reviews for governance[cite: 1, 2].

---

## 🛠️ Built With & Technologies Used
* **Microsoft Entra ID (Azure AD)** (Users, Groups, Dynamic Rules)[cite: 1, 2]
* **Conditional Access Policies** (MFA Enforcement & Risk Signals)[cite: 1, 2]
* **Privileged Identity Management (PIM)** (Just-In-Time Elevation & Approvals)[cite: 1, 2]
* **Entra ID Access Reviews** (Identity Lifecycle & Governance)[cite: 1, 2]

---

## 🎯 Key Implementation Steps

1. **Identity Provisioning:** Configured an Entra ID tenant structure featuring user accounts, administrative units, and dynamic user groups[cite: 1, 2].
2. **Zero Trust Conditional Access:** Constructed a Conditional Access policy requiring Multi-Factor Authentication (MFA) for cloud access while enforcing location-based blocking rules[cite: 1, 2].
3. **Privileged Identity Management (PIM):** Configured Just-In-Time (JIT) role activation rules requiring formal approval workflows before elevating privileges to highly privileged roles[cite: 1, 2].
4. **Access Governance:** Set up periodic Access Reviews to evaluate and revoke unnecessary role assignments following least-privilege principles[cite: 1, 2].

---

## 🖼️ Verification & Proof of Concept

*(Drop 2–3 screenshots here demonstrating a Conditional Access policy rule, a PIM role approval prompt, or Sign-In logs)*[cite: 1, 4]

- `![Conditional Access Policy](./screenshots/conditional-access.png)`
- `![PIM Role Activation Workflow](./screenshots/pim-activation.png)`
- `![Access Review Portal](./screenshots/access-review.png)`
