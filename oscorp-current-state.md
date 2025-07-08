# Oscorp Current State Overview

_Summary of Oscorp's cybersecurity posture based on initial stakeholder interview and documentation review._

---

## 👥 Team Structure

- **Cybersecurity Analyst**: Generalist, responds to incidents. Reports to IT Manager.
- **Network Engineer**: Manages firewalls. Reports to Network Team Leader.
- **Cybersecurity Consultant** _(you)_: Reports initially to IT Manager.

---

## 🧱 Organizational Governance

- No defined cybersecurity strategy or roles
- Cyber responsibilities assigned to generalist IT staff

---

## 💻 Asset Management

- Laptops tracked in a spreadsheet (includes serials, models, warranties)
- Microsoft Office 365 and Azure used for all data and services
- Secure Operating Environment (SOE) used to image laptops

---

## 🔁 Business Continuity & Disaster Recovery

- Regular DR testing is conducted
- Clear, documented business continuity plans exist
- Backups are taken and periodically tested

---

## 🩹 Vulnerability Management

- Qualys scanner purchased and used on an ad hoc basis
- No formal vulnerability management program
- Large number of high and severe vulnerabilities reported

---

## 📉 Risk Management

- A financial risk team exists
- No cybersecurity or technology-specific risk management processes

---

## 🔗 Third-Party Risk

- No formal third-party risk management program
- Vendor contracts reviewed by finance and procurement only — no security involvement

---

## 🛂 Identity & Access Management

- Active Directory used for identity and group management
- No MFA, PAM, or SoD enforcement
- Shared admin passwords among IT leadership
- VPN used for remote access

---

## 🌐 Network Security

- Palo Alto Next Gen firewalls deployed
- Firewalls configured, updated, and audited by the network team
- Cloud-inclusive network diagrams maintained
- VLAN-based segmentation implemented

---

## 🏢 Physical Security

- 24/7 monitored, high-security facility with modern CCTV
- Strong employee vetting for lab access and general roles

---

## 🧾 Data Security

- No Data Loss Prevention (DLP) solution in place
- All organizational data resides in Azure and Office 365
- Critical SaaS platform hosted by Horizon Labs

---

## 📜 Policy

- Only a generic IT policy exists
- No formal policies for information security, data classification, or governance

---

## 🚨 Detection & Response

- No centralized detection or formal IR capabilities
- Microsoft Defender is deployed, but not centrally monitored
- No SIEM or alert correlation in place

---

## 🧠 Security Awareness

- All staff complete a basic cybersecurity module during onboarding
- No recurring or role-based training implemented
