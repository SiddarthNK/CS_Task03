# Vulnerability Scan Report

## 📌 Overview
This report presents the results of a vulnerability assessment performed on a local machine using Nessus Essentials. The purpose of the scan was to identify security weaknesses that could potentially be exploited by attackers and recommend mitigation measures.

---

## 🛠 Tool Used
- **Scanner:** Nessus Essentials  
- **Scan Type:** Basic Network Scan  
- **Target:** localhost (127.0.0.1)  
- **Scan Duration:** ~XX minutes  
- **Date Performed:** [Add Date]

---

## 🎯 Scan Objective
The objective of this scan was to:

- Detect known vulnerabilities
- Identify outdated software
- Examine network exposure
- Evaluate system security posture

---

## 📊 Vulnerability Summary

| Severity | Number of Vulnerabilities |
|--------|---------------------------|
| Critical | X |
| High | X |
| Medium | X |
| Low | X |
| Informational | X |

> **Note:** Severity classification is based on the Common Vulnerability Scoring System (CVSS).

---

## 🔍 Key Findings

### ✅ 1. Missing Security Updates
**Severity:** High  

**Description:**  
The scanner detected that the operating system is missing important security patches. Unpatched systems are common attack targets because vulnerabilities are publicly documented.

**Risk:**  
Attackers may exploit these weaknesses to gain unauthorized access or execute malicious code.

**Recommended Fix:**  
- Install the latest operating system updates.
- Enable automatic updates.

---

### ✅ 2. Outdated Software Detected
**Severity:** Medium / High  

**Description:**  
Some installed applications are not running the latest versions, which may contain known security flaws.

**Risk:**  
Outdated software increases exposure to malware and remote exploitation.

**Recommended Fix:**  
- Update all applications to their latest versions.
- Remove unsupported software.

---

### ✅ 3. Open Network Ports
**Severity:** Medium  

**Description:**  
The scan identified open ports that may allow external connections.

**Risk:**  
Unnecessary open ports increase the attack surface of the system.

**Recommended Fix:**  
- Close unused ports.
- Disable unnecessary services.
- Configure firewall rules.

---

### ✅ 4. Weak Encryption Configuration
**Severity:** Low  

**Description:**  
The system supports older encryption protocols that are no longer considered secure.

**Risk:**  
Attackers could intercept sensitive data.

**Recommended Fix:**  
- Disable deprecated protocols.
- Enforce modern encryption standards.

---

## 📷 Evidence
Screenshots of the scan configuration, progress, and final results are available in the **/screenshots** directory of this repository.

---

## ⚠️ Limitations of the Scan
- The scan was performed on a local machine only.
- Results depend on currently available plugins.
- Some vulnerabilities may require authenticated scans for deeper detection.

---

## ✅ Conclusion
The vulnerability scan successfully identified several security issues ranging from low to high severity.  

Most risks can be mitigated through:

- Regular system updates  
- Software patching  
- Proper firewall configuration  
- Disabling unnecessary services  

Performing periodic vulnerability scans is essential for maintaining a strong security posture and reducing the likelihood of cyber attacks.

---

## 🎯 Outcome
This task provided hands-on experience with vulnerability scanning tools and improved understanding of common system security risks and their remediation.
