# CIS Controls (Center for Internet Security Controls)

## Introduction
The **CIS Controls** (formerly known as the *SANS Top 20 Critical Security Controls*) are a globally recognized set of **cybersecurity best practices** developed by the **Center for Internet Security (CIS)**.  
They provide a **prioritized, actionable framework** to help organizations protect themselves against the most pervasive and dangerous cyber threats.

Unlike broad governance frameworks such as **ISO 27001** or **NIST CSF**, the CIS Controls are **prescriptive and technically focused**, making them highly practical for IT professionals and cybersecurity teams to implement.

---

## Purpose and Objectives
The CIS Controls were designed to:

- Identify and mitigate the most common cyberattack techniques.
- Establish a prioritized roadmap for cybersecurity improvement.
- Provide measurable, implementable, and verifiable security actions.
- Align technical security operations with broader frameworks (e.g., NIST CSF, ISO 27001).
- Help organizations of any size build resilience against modern threats.

In short, the CIS Controls bridge the gap between **high-level security policies** and **hands-on technical defenses**.

---

## Evolution of the CIS Controls
The CIS Controls have evolved over time to match the changing threat landscape:

| Version | Year | Key Updates |
|----------|------|-------------|
| **v1–v5** | 2008–2010 | Focused on top 20 critical controls derived from U.S. defense experiences. |
| **v6–v7** | 2015–2018 | Streamlined controls, aligned with NIST standards, and enhanced usability. |
| **v8** | 2021 | Consolidated from 20 controls into **18**, reflecting cloud, mobility, and modern IT environments. |

**Version 8** is the most current, reorganized to emphasize asset management, continuous monitoring, and automation.

---

## Structure of the CIS Controls v8
The CIS Controls v8 consist of **18 high-level controls**, each broken down into **specific safeguards (sub-controls)** — 153 in total.  
These safeguards are grouped into **Implementation Groups (IGs)** that guide organizations based on their size, resources, and cybersecurity maturity.

### 🔹 Implementation Groups (IGs)
| Group | Description | Typical Organization Type |
|--------|--------------|----------------------------|
| **IG1 – Basic Cyber Hygiene** | Foundational safeguards that all organizations should implement. | Small organizations or those with limited IT/security resources. |
| **IG2 – Intermediate** | Adds depth with more detailed monitoring, access, and defense mechanisms. | Medium-sized organizations with dedicated IT teams. |
| **IG3 – Advanced** | Comprehensive protections against sophisticated adversaries. | Large enterprises or high-value target organizations (e.g., finance, defense). |

---

## The 18 CIS Controls (v8 Overview)

### 1. **Inventory and Control of Enterprise Assets**
Maintain an accurate inventory of all hardware assets (servers, workstations, IoT, mobile) connected to the network.  
→ Prevent unauthorized and unmanaged devices from introducing vulnerabilities.

### 2. **Inventory and Control of Software Assets**
Track, manage, and authorize all software within the environment.  
→ Prevent installation of unapproved or malicious software.

### 3. **Data Protection**
Identify, classify, and secure sensitive data both in transit and at rest.  
→ Protect the confidentiality, integrity, and availability of critical information.

### 4. **Secure Configuration of Enterprise Assets and Software**
Harden configurations of operating systems, applications, and network devices.  
→ Reduce the attack surface by disabling unnecessary features and services.

### 5. **Account Management**
Actively manage user accounts and access permissions.  
→ Ensure users have only the privileges necessary to perform their roles.

### 6. **Access Control Management**
Implement role-based access control (RBAC), multi-factor authentication (MFA), and session management.  
→ Prevent unauthorized access and privilege escalation.

### 7. **Continuous Vulnerability Management**
Routinely scan for vulnerabilities and apply timely remediation.  
→ Reduce exploitable weaknesses through proactive patching.

### 8. **Audit Log Management**
Collect, protect, and analyze audit logs from systems and applications.  
→ Detect anomalies and support incident investigations.

### 9. **Email and Web Browser Protections**
Configure browsers, filters, and email systems to reduce phishing, malware, and drive-by attacks.  
→ Defend against common vectors of initial compromise.

### 10. **Malware Defenses**
Deploy and manage anti-malware solutions and endpoint detection tools.  
→ Detect, block, and recover from malicious code execution.

### 11. **Data Recovery**
Implement secure, tested backups for critical systems and data.  
→ Enable recovery in case of ransomware or data loss.

### 12. **Network Infrastructure Management**
Secure and maintain network devices such as routers, firewalls, and switches.  
→ Prevent unauthorized access and maintain secure connectivity.

### 13. **Network Monitoring and Defense**
Monitor network traffic and deploy intrusion detection/prevention systems.  
→ Identify and respond to malicious network activity.

### 14. **Security Awareness and Skills Training**
Provide regular training to employees on cybersecurity best practices.  
→ Cultivate a security-conscious workforce.

### 15. **Service Provider Management**
Evaluate and monitor third-party vendors’ security posture.  
→ Ensure supply chain and outsourced services maintain compliance.

### 16. **Application Software Security**
Secure application development through coding standards, testing, and review.  
→ Prevent software vulnerabilities like SQL injection or XSS.

### 17. **Incident Response Management**
Establish and maintain an incident response process.  
→ Detect, respond, and recover effectively from cyber incidents.

### 18. **Penetration Testing**
Conduct periodic red team and penetration testing exercises.  
→ Identify gaps and validate the effectiveness of existing controls.

---

## CIS Controls vs. Other Frameworks

| Framework | Focus | CIS Relationship |
|------------|--------|------------------|
| **NIST CSF** | Strategic, risk-based framework for managing cybersecurity. | CIS Controls align as technical implementations of NIST functions. |
| **ISO/IEC 27001** | Information security management systems (ISMS). | CIS provides operational detail for ISO security controls. |
| **SOC 2 / SOX** | Data integrity and reporting assurance. | CIS supports technical compliance for confidentiality and integrity. |
| **PCI DSS** | Payment card security. | CIS offers best practices that overlap with PCI control requirements. |

CIS Controls are often used **in combination** with these frameworks to provide actionable technical defenses for compliance mandates.

---

## Benefits of Implementing CIS Controls
Implementing CIS Controls helps organizations:

- **Reduce risk** from the most common cyber threats.  
- **Establish repeatable and measurable security processes.**  
- **Enhance compliance alignment** with NIST, ISO, and regulatory standards.  
- **Increase operational resilience** through automation and monitoring.  
- **Prioritize security investments** for maximum impact.

---

## Common Implementation Challenges
1. **Asset visibility** — many organizations struggle to track shadow IT and unmanaged endpoints.  
2. **Resource constraints** — implementing advanced controls (IG2, IG3) requires staff and budget.  
3. **Change management** — balancing security hardening with operational flexibility.  
4. **Data classification** — identifying what constitutes “sensitive” data across departments.  
5. **Tool integration** — aligning disparate IT and security tools under a unified framework.

---

## CIS Controls and Cybersecurity Maturity
The CIS Controls naturally support the **cybersecurity maturity model**:

| Level | Description | Key Focus |
|--------|--------------|-----------|
| **Level 1** | Reactive | Basic visibility and hygiene (IG1). |
| **Level 2** | Managed | Process-driven control implementation (IG2). |
| **Level 3** | Optimized | Continuous monitoring and proactive defense (IG3). |

Organizations can assess maturity using the **CIS Risk Assessment Method (CIS RAM)**, a companion framework to CIS Controls that helps balance security with business needs.

---

## Auditing and Verification
CIS compliance is **not a legal requirement** but a **recognized security benchmark**.  
Organizations can perform internal or third-party audits using:
- CIS Controls Assessment Tool (CIS-CAT).  
- Automated security configuration benchmarks.  
- Continuous compliance dashboards (e.g., via SIEMs or GRC tools).  

The CIS also publishes **CIS Benchmarks** — detailed configuration guides for securing systems like Windows, Linux, macOS, Cisco, and cloud platforms (AWS, Azure, GCP).

---

## Conclusion
The **CIS Controls** provide one of the most practical and battle-tested frameworks for building a strong cybersecurity foundation.  
By focusing on **prioritization, implementation, and continuous monitoring**, organizations can systematically defend against real-world threats.

Whether an enterprise, SMB, or public institution, adopting the CIS Controls leads to measurable improvements in security posture, data protection, and resilience — serving as both a **technical blueprint** and **strategic roadmap** for cybersecurity maturity.

---

## 📫 About Me
- ✉️ **Email:** [dimejioyemarky@gmail.com](mailto:dimejioyemarky@gmail.com)  
- 🔗 **LinkedIn:** [Oladimeji Oyediran](https://www.linkedin.com/in/oladimeji-oyediran-657658238)
