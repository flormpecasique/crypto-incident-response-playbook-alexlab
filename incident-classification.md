# Incident Classification & Severity Levels

## 📌 Purpose
This document defines how security incidents are **classified, prioritized, and escalated** within the context of crypto and DeFi environments.

A clear classification model helps security teams **respond faster**, allocate resources efficiently, and reduce impact.

---

## 🧩 Incident Categories

### 1. Critical Incidents
**Description:**
- Active exploitation of smart contracts
- Large-scale fund drainage
- Compromise of admin or multisig keys
- Bridge exploitation affecting multiple chains

**Impact:**
- Severe financial loss
- Loss of protocol integrity
- Immediate reputational damage

**Response Priority:** Immediate (24/7)

---

### 2. High Severity Incidents
**Description:**
- Suspicious on-chain behavior with confirmed malicious intent
- Partial loss of funds
- Unauthorized parameter or configuration changes
- Exploit attempts that were partially mitigated

**Impact:**
- High financial or operational risk
- Potential escalation to critical

**Response Priority:** High (within hours)

---

### 3. Medium Severity Incidents
**Description:**
- Abnormal transactions without confirmed exploitation
- Alerts triggered by monitoring systems
- Failed attack attempts
- Misconfigurations detected early

**Impact:**
- Limited operational impact
- Potential security weakness

**Response Priority:** Medium (same business day)

---

### 4. Low Severity Incidents
**Description:**
- False positives
- Minor anomalies with no security impact
- Informational alerts

**Impact:**
- No direct risk to assets or users

**Response Priority:** Low (monitor and document)

---

## 🚦 Severity Determination Criteria
Incident severity is determined based on:

- Financial impact (actual or potential)
- Scope of affected assets or users
- Exploitability and attack complexity
- Ongoing attacker activity
- Reputational and regulatory impact

---

## 🔁 Escalation Matrix

| Severity  | SOC Action                  | Escalation Required |
|---------|-----------------------------|---------------------|
| Critical | Immediate containment       | Security Lead, Legal, Management |
| High    | Rapid investigation         | Security Lead |
| Medium  | Investigation & monitoring  | SOC Lead |
| Low     | Documentation & tracking    | None |

---

## 🧠 Analyst Notes
- When in doubt, **classify higher rather than lower**
- Reclassification is allowed as new evidence emerges
- All incidents must be documented, regardless of severity

---

## ✅ Summary
A consistent incident classification framework enables **faster response, clearer communication, and better decision-making** during security events.
