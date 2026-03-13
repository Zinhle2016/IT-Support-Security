# IT Security Audit: Defense Against the Digital Dark Arts 
(IT Support Professional Certificate)

--- Introduction

In the evolving landscape of cybersecurity, "Defense Against the Digital Dark Arts" requires a proactive approach to system hardening. This audit focuses on identifying vulnerabilities within a local environment—specifically targeting authentication weaknesses, network exposure, and outdated software. By performing this system check, I have simulated the role of an IT Support Specialist ensuring that a workstation is resilient against common attack vectors like unauthorized access and malware exploitation.

## Security Audit Checklist

### 1. Encryption & Authentication
* **Status:** Manual Audit Performed.
* **Observation:** System required a password configuration update to meet complexity standards.
* **Action Taken:** Implemented a high-entropy passphrase and audited sign-in options.
* **Evidence:** See `s1.png` (Password Configuration Setup).

### 2. Firewall & Network Protection
* **Status:** ✅ Active
* **Observation:** Firewall is currently active across Domain, Private, and Public network profiles.
* **Action Taken:** Verified that the "Private" network is active and unauthorized inbound traffic is restricted.
* **Evidence:** See `s3.png` (Firewall & Network Protection Status).

### 3. Software Updates & Patch Management
* **Status:** ⚠️ Critical Action Required
* **Observation:** System identified as missing important security and quality fixes. It is currently at the "End of Support" phase for the current OS version.
* **Improvement Suggestion:** Enroll in Extended Security Updates (ESU) or perform a clean install of a supported OS version to ensure continued protection against vulnerabilities.
* **Evidence:** See `s2.png` (Windows Update Audit).

---

## Security Best Practices Applied
1. **Principle of Least Privilege:** Audited user accounts to ensure administrative rights are only used when necessary.
2. **Attack Surface Reduction:** Confirmed firewall status to minimize open ports available to external threats.
3. **Defense in Depth:** Combined authentication updates with network-level filtering for a layered security approach.

---

## Technical Evidence
*Click the links below to view the audit screenshots:*
<img width="1026" height="797" alt="image" src="https://github.com/user-attachments/assets/dbb8c22c-9542-41dd-abe7-eba3ed78fbf7" />

<img width="1012" height="767" alt="image" src="https://github.com/user-attachments/assets/eb5a291d-15d1-48cf-abb3-e4797fdabc98" />

<img width="1018" height="787" alt="image" src="https://github.com/user-attachments/assets/32994712-d2ec-43ab-b025-f42fa1425d43" />


Executive Summary


This audit provides a high-level overview of the security posture for a local workstation as of February 13, 2026. The evaluation focused on reducing the system's attack surface through three pillars: Identity, Network, and Maintenance.

While Network Defense is robust with an active, multi-profile Firewall, the Endpoint Security is currently at high risk due to the "End of Support" status of the OS. The implementation of a new password policy serves as a temporary mitigant, but the primary recommendation is a full system migration to a supported version to ensure long-term resilience against modern exploits.
