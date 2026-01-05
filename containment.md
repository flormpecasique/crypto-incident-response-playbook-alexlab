# Containment Strategies

## 📌 Purpose
This document outlines how to **contain a crypto-related security incident** to prevent further loss of funds or compromise of protocol integrity.

Containment is a **critical step**: it stabilizes the situation while analysis and recovery are ongoing.

---

## 🛡️ Containment Objectives
- Stop active exploitation
- Limit financial damage
- Preserve evidence for investigation
- Protect unaffected assets and users
- Maintain communication with stakeholders

---

## 🔒 Containment Measures

### 1. Contract & Wallet Controls
- **Pause or freeze contracts** if emergency functions exist
- **Multisig key checks**: ensure no unauthorized signatures were used
- **Revoke or rotate keys** affected by compromise
- **Isolate affected wallets** and prevent outgoing transactions

### 2. Network & Infrastructure
- Restrict access to admin dashboards
- Block suspicious IPs or nodes
- Verify and secure CI/CD pipelines or backend services

### 3. Transaction Monitoring
- Monitor real-time on-chain activity
- Set alerts for unusual transfers or liquidity changes
- Track cross-chain activity if bridges are involved

### 4. External Collaboration
- Notify blockchain analytics providers if needed
- Inform external security partners or auditors
- Coordinate with exchanges if funds may reach hot wallets

---

## 🧠 Decision Guidelines
- Containment should **minimize disruption** while **stopping active threats**
- Avoid drastic actions that may **further harm users or assets**
- Containment measures must be **documented and reversible** if possible

---

## 🔁 Continuous Evaluation
- Reassess containment effectiveness every 15–30 minutes during active incidents
- Update severity and escalation matrix if containment fails or attack spreads
- Ensure logs and evidence are preserved for post-incident review

---

## ✅ Summary
Proper containment prevents escalation and **buys time** for recovery and remediation while protecting assets and stakeholders.
