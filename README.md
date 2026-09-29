# GOY Foundation Information Security & Cybersecurity Policy

**Document Control & Metadata**
* **Organization:** GOY Foundation
* **Author:** Emmanuel Udobi (Junior Cybersecurity Officer)
* **Document Reference:** GOY-SEC-POL-2026-v1.0
* **Classification:** Internal Policy
   * **Effective Date:** October 29 2026
* **Next Review Date:** march 29, 2027
* **Target Audience:** All Staff, Volunteers, Contractors, System Administrators

---

## 1. Executive Summary & Purpose
The **GOY Foundation** relies on digital infrastructure, network endpoints, and cloud systems to carry out its core non-profit and organizational objectives This policy establishes mandatory operational security baselines designed to ensure the **Confidentiality, Integrity, and Availability (CIA)** of organizational assets and sensitive data against modern cyber threats.

Key Strategic Objectives:
1. Prevent unauthorized access to sensitive financial, donor, volunteer, and operational data.
2. Maintain operational resilience and rapid recovery capabilities in the event of security incidents.
3. Establish clear administrative, technical, and physical accountability across all departments.

---

## 2. Scope & Applicability
This policy applies to:
* All full-time, part-time, temporary staff, volunteers, and third-party contractors associated with the **GOY Foundation**
* All physical endpoints (laptops, mobile devices, servers) and logical environments (cloud storage, code repositories, email platforms).
* Both office network infrastructure and remote work environments (including Bring Your Own Device - BYOD settings).

---

## 3. Organizational Core Security Policies

### 3.1 Identity & Access Management (IAM)
* **Principle of Least Privilege (PoLP):** User accounts will be granted access rights strictly necessary for their documented job functions.
* **Multi-Factor Authentication (MFA):** MFA is mandatory across all corporate Google Workspace, GitHub, portal, and email logins.
* **Password Policy Standards:**
  * Minimum length of **14 characters**.
  * Must contain uppercase, lowercase, numerical, and special characters.
  * Prohibition of default, shared, or plaintext passwords.
  * Mandatory immediate revocation of access upon employment termination.

### 3.2 Endpoint & Network Security Controls
* **Endpoint Protection:** All devices connecting to organizational resources must run active, updated Anti-Virus/Endpoint Detection and Response (EDR) agents and active OS firewalls.
* **Workstation Hygiene:** Screen auto-lock must trigger after 3 minutes of inactivity. Screen locking (`Win + L` or `Cmd + Ctrl + Q`) is required whenever stepping away.
* **Remote Access & Wi-Fi:** Untrusted public Wi-Fi networks must only be accessed through an enterprise-approved Virtual Private Network (VPN).

### 3.3 Data Protection, Encryption & Hygiene
* **Data Classification Scheme:** Data must be handled according to three tiers:
  * *Public:* Open for general release.
  * *Internal:* Restricted to GOY Foundation personnel.
  * *Confidential:* Sensitive operational, volunteer, or financial data requiring restricted access.
* **Encryption Baselines:**
  * **Data in Transit:** All network communication must use modern cryptographic protocols (TLS 1.3 / HTTPS).
  * **Data at Rest:** Endpoints and database backups must utilize standard full-disk encryption (BitLocker / FileVault / AES-256).
* **Backup & Retention Policy:** Automated weekly off-site cloud backups following the 3-2-1 backup rule (3 copies, 2 different media, 1 offsite).

### 3.4 Security Awareness & Phishing Prevention
* **Email Safeguards:** External sender warnings are enabled. Staff must refrain from opening unrecognized email attachments or clicking untrusted links.
* **Social Engineering Defense:** Sensitive operational or financial transactions requested via email or messaging must be verified through a secondary out-of-band channel.

---

## 4. Incident Response & Threat Reporting
All suspected security anomalies—including lost hardware, potential phishing clicks, unauthorized account activity, or system compromises—must be reported immediately.

* **Reporting Channel:** Contact `security@goyfoundation.org` (or designated IT Admin).
* **Initial Containment Procedure:**
  1. The affected account or device will be immediately isolated from the network.
  2. Active sessions will be invalidated and credentials reset.
  3. Log analysis will be performed to assess scope and data exposure.

---

## 5. Compliance, Enforcement & Review
* **Enforcement:** Non-compliance with this policy compromises organizational security and may result in revocation of access privileges or administrative disciplinary action.
* **Review Cycle:** This policy is subject to formal review annually or immediately following any significant operational change or security incident.
