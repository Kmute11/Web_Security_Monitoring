# Web Security Monitoring: Payment Gateway Attack

## Overview
Configured and implemented Elastic SIEM and Splunk to monitor security events and detect potential threats. Performed log analysis to identify vulnerabilities, including payment gateway traversal and UI functionality issues,using both platforms. Conducted real-time threat detection and response by setting up alerts for brute-force login attempts, unauthorized payment activities, and data breaches. Collaborated with the development team to address identified vulnerabilities, improving the overall security posture.

## Key Vulnerabilities

### CVE-2021-45046
**Description:**
This vulnerability in the Apache Log4j2 library allows an attacker to craft malicious input data that causes information leaks and, in some cases, remote code execution (RCE) under specific configurations.

**CVSS Score:**
- **Attack Vector (AV):** Network (N)
- **Attack Complexity (AC):** Low (L)
- **Privileges Required (PR):** None (N)
- **User Interaction (UI):** None (N)
- **Scope (S):** Changed (C)
- **Confidentiality Impact (C):** High (H)
- **Integrity Impact (I):** High (H)
- **Availability Impact (A):** High (H)

**Base Score:** 9.0 (Critical)

### CVE-2019-12384
**Description:**
A vulnerability in Jackson, a popular JSON library, allows deserialization of malicious objects, leading to remote code execution (RCE).

**CVSS Score:**
- **Attack Vector (AV):** Network (N)
- **Attack Complexity (AC):** Low (L)
- **Privileges Required (PR):** None (N)
- **User Interaction (UI):** None (N)
- **Scope (S):** Unchanged (U)
- **Confidentiality Impact (C):** High (H)
- **Integrity Impact (I):** High (H)
- **Availability Impact (A):** High (H)

**Base Score:** 9.8 (Critical)
