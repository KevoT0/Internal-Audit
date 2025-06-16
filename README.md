# Internal-Audit

# 🌐 Information Security Risk Assessment Portfolio

## 📌 Project Overview

**Objective:**  
Conduct an internal audit to identify gaps against ISO/IEC 27001:2022 controls and recommend remediation plans to improve the organizational security posture.

**Scope:**  
This assessment focused on four critical control domains:
- Logging & Monitoring  
- Policy Gaps  
- Media Encryption  
- Asset Inventory

**Standards Applied:**  
ISO/IEC 27001:2022 — Annex A (Controls A.5 to A.8)

---

## 🔍 Findings & Risk Treatment Plan

### 🛑 Finding 1: Inadequate Logging and Monitoring

- **Implication:** Inability to detect unauthorized access and system anomalies, breaching the CIA triad.
- **ISO 27001:2022 Clause:** A.8.15, A.8.16  
- **Risk Level:** High  
- **Remediation Plan:**
  - Deploy SIEM, IDS/IPS
  - Configure firewall rules
  - Retain logs for a minimum of 30 days
  - Conduct regular penetration testing and vulnerability assessments
- **Timeline:** 2 Months  
- **Owner:** IT Security

---

### 🛑 Finding 2: Missing Acceptable Use Policy (AUP)

- **Implication:** Risk of data misuse and reputational damage due to inappropriate device usage
- **ISO 27001:2022 Clause:** A.5.1, A.6.2  
- **Risk Level:** High  
- **Remediation Plan:**
  - Draft and implement AUP aligned with business strategy
  - Schedule annual policy reviews
  - Integrate AUP into employee onboarding
  - Require employee acknowledgment of policy
- **Timeline:** 5 Weeks  
- **Owner:** HR Department

---

### 🛑 Finding 3: Unencrypted USB Drive

- **Implication:** Unauthorized access or corruption of sensitive data stored on removable media
- **ISO 27001:2022 Clause:** A.7.10  
- **Risk Level:** High  
- **Remediation Plan:**
  - Enforce encryption on all USB and removable devices
  - Block usage of unencrypted devices via endpoint controls
  - Conduct user awareness sessions
- **Timeline:** 3 Weeks  
- **Owner:** IT Security

---

### 🛑 Finding 4: Incomplete Asset Inventory

- **Implication:** Data loss and lack of accountability for hardware managed by ex-staff
- **ISO 27001:2022 Clause:** A.5.9  
- **Risk Level:** Medium  
- **Remediation Plan:**
  - Implement a centralized asset inventory system
  - Maintain records with ownership and status
  - Conduct quarterly audits
  - Integrate asset offboarding into HR/IT processes
- **Timeline:** 2 Months  
- **Owner:** IT Security

---

## 📋 Risk Register

| Risk ID | Description | Likelihood | Impact | Risk Level | Mitigation | Owner | Status | ISO Ref |
|--------|-------------|------------|--------|------------|------------|-------|--------|---------|
| R-01 | Inadequate logging and monitoring could allow unauthorized access to go undetected | High | High | Critical | Deploy SIEM, IDS/IPS, retain logs, conduct pen testing | IT Security | Open | A.8.15, A.8.16 |
| R-02 | Missing Acceptable Use Policy (AUP) could lead to breaches of confidentiality | High | High | Critical | Implement AUP and policy reviews | HR | Open | A.5.1, A.6.2 |
| R-03 | Unencrypted USB drive risks data leakage | High | High | Critical | Enforce encryption, block unsecure devices | IT Security | Open | A.7.10 |
| R-04 | Incomplete asset inventory risks data loss or leaks during offboarding | Low | Medium | Medium | Maintain and regularly review asset inventory | IT Security | Open | A.5.9 |

---

## ✅ Summary

This internal audit has helped identify critical vulnerabilities mapped directly to ISO/IEC 27001:2022 controls. Each finding is accompanied by a remediation plan and owner accountability. The improvement roadmap ensures alignment with best practices and regulatory expectations, enhancing the organization's security maturity.

---

#ISO27001 #CyberSecurity #RiskAssessment #ITAudit #InformationSecurity #SIEM #InternalControls #ITGovernance #SecurityPolicy
