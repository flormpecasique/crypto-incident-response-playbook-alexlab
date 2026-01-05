# Detection & Analysis

## 📌 Purpose
This document describes how potential security incidents are **detected, validated, and analyzed** in crypto and DeFi environments.

Early detection and accurate analysis are critical to **limit financial and operational damage** during an active exploit.

---

## 🚨 Detection Sources
Security incidents may be detected through multiple channels:

- On-chain monitoring tools and alerts
- Abnormal transaction volume or value
- Unexpected smart contract behavior
- Third-party security notifications
- Community or user reports
- Internal anomaly detection rules

---

## 🔍 Common Indicators of Compromise (IoCs)

### On-Chain Indicators
- Sudden spikes in transaction frequency
- Large transfers to newly created wallets
- Repeated contract calls with unusual parameters
- Liquidity pool imbalance or rapid drain
- Cross-chain transfers shortly after fund movement

### Off-Chain Indicators
- Unauthorized changes to infrastructure configurations
- Suspicious access to admin dashboards or CI/CD pipelines
- Alerts from blockchain analytics providers
- Internal logs showing abnormal access patterns

---

## 🧪 Initial Triage Process
When an alert is triggered:

1. Confirm alert validity (rule accuracy, false positive check)
2. Identify affected contracts, wallets, or bridges
3. Determine whether exploitation is ongoing
4. Estimate potential financial impact
5. Assign preliminary severity level

---

## 🧠 Analysis Questions
During analysis, analysts should answer:

- Is this behavior expected or anomalous?
- Is there evidence of malicious intent?
- Are funds actively being drained?
- Which assets and users are affected?
- Can the attack propagate further?

---

## 🧾 Evidence Collection
Preserve all relevant evidence:

- Transaction hashes
- Wallet addresses involved
- Block numbers and timestamps
- Relevant logs and alerts
- Screenshots or dashboards (if applicable)

Evidence must be **immutable and time-stamped**.

---

## 🔁 Reassessment
Incident severity and scope must be **continuously reassessed** as new information becomes available.

Escalation should occur immediately if:
- Exploitation becomes active
- Financial impact increases
- Critical assets are affected

---

## ✅ Summary
Effective detection and analysis enable security teams to **move quickly, reduce uncertainty, and make informed containment decisions** during crypto security incidents.
