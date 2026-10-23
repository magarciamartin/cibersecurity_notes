# cibersecurity_notes
A core cybersecurity stack of software, platforms, and open-source utilities designed to monitor, detect, analyze, and respond to cyber threats.
# Core Cybersecurity Software & Tool Stack

A curated blueprint of the foundational software platforms, security tools, and infrastructure components required to build a modern Enterprise Security Architecture.

## 📊 Quick Overview Table

| Layer | Functional Area | Key Technologies |
| --- | --- | --- |
| **SIEM & Analytics** | Threat Detection & Logs | Splunk, Elastic Security, OpenSearch |
| **Endpoint Security** | EDR / XDR | CrowdStrike Falcon, Microsoft Defender |
| **Network & Perimeter** | NGFW / Zero Trust | Palo Alto Networks, Fortinet, Wireshark |
| **Identity (IAM)** | Access Control & Auth | Microsoft Entra ID, Okta, HashiCorp Vault |
| **Vulnerability Mgmt** | Assessment & Scanning | Tenable Nessus, Qualys, Burp Suite |
| **DevSecOps** | Application Security | Snyk, SonarQube, Trivy |

---

## 🛠️ Deep Dive: The Core Layers

### 1. Security Information and Event Management (SIEM)
*   **[Splunk](https://splunk.com)**: Industry-standard enterprise log aggregation and advanced security analytics engine.
*   **[Elastic Security](https://elastic.co)**: Open-core SIEM providing real-time search, logs analysis, and endpoint monitoring capabilities.

### 2. Endpoint Detection and Response (EDR)
*   **[CrowdStrike Falcon](https://crowdstrike.com)**: Cloud-native endpoint security platform covering threat intelligence and response.
*   **[Microsoft Defender for Endpoint](https://microsoft.com)**: Integrated enterprise endpoint security platform for preventative protection and post-breach detection.

### 3. Identity and Access Management (IAM)
*   **[Microsoft Entra ID](https://microsoft.com)**: Comprehensive cloud identity and access management solution.
*   **[HashiCorp Vault](https://vaultproject.io)**: Secure secret management, encryption keys, passwords, and API certificates tracker.

### 4. Vulnerability & Application Security (DevSecOps)
*   **[Tenable Nessus](https://tenable.com)**: Widely trusted vulnerability scanner for point-in-time assessments.
*   **[Snyk](https://snyk.io)**: Developer-first security platform for scanning code, dependencies, containers, and IaC templates.

---

## 🚀 How to Use This Blueprint
1. **Assess Your Perimeter:** Identify gaps in your current stack using the core layers above.
2. **Implement Zero Trust:** Prioritize Identity (IAM) and Network Microsegmentation layers first.
3. **Automate Logging:** Establish your SIEM tier before deploying massive endpoint fleets.

## 🤝 Contributing
Contributions are welcome! Please read the `CONTRIBUTING.md` file before submitting a Pull Request to add new open-source or enterprise security tools.

