# OS-Security-Task-2-Kali-linux-
# Operating System Security Hardening – Kali Linux

## Cyber Security Internship | Task 2

---

## Executive Summary
This repository documents the practical implementation of **Operating System (OS) security hardening**
using **Kali Linux**. The task focuses on reducing the system attack surface by enforcing
proper user privilege management, secure file permissions, firewall configuration,
process monitoring, and service minimization.

The objective is to demonstrate an understanding of **OS-level defense mechanisms**
that are critical in securing Linux-based systems against unauthorized access
and post-exploitation risks.

---

## Scope of Work
The scope of this task includes:
- Linux user and privilege management
- Permission and ownership control
- Network-level protection using firewall rules
- Process and service inspection
- Application of OS hardening principles aligned with security best practices

---

## Environment & Tooling
- **Operating System:** Kali Linux (Debian-based)
- **Privilege Management:** sudo, root access
- **File System Security:** chmod, chown
- **Firewall:** UFW (Uncomplicated Firewall)
- **Process Monitoring:** ps, top
- **Service Management:** systemctl
- **Version Control:** GitHub

---

## Technical Implementation

### 1. User Privilege & Access Control
- Enumerated system users via `/etc/passwd`
- Distinguished between **root**, **privileged**, and **non-privileged** users
- Configured controlled administrative access using `sudo`
- Applied the **Principle of Least Privilege (PoLP)** to reduce misuse of elevated permissions

**Security Impact:**  
Limits damage caused by compromised accounts and prevents unauthorized system-wide changes.

---

### 2. File Permission & Ownership Enforcement
- Audited file permissions using `ls -l`
- Implemented strict permission models using `chmod`
- Enforced proper ownership using `chown`
- Prevented unauthorized file access and modification

**Security Impact:**  
Mitigates risks such as privilege escalation, data tampering, and unauthorized execution.

---

### 3. Firewall Configuration & Network Protection
- Installed and enabled UFW firewall
- Verified firewall status and default policies
- Restricted unnecessary inbound connections

**Security Impact:**  
Reduces exposure to network-based attacks by filtering unauthorized traffic at the OS level.

---

### 4. Process Visibility & Runtime Monitoring
- Enumerated active processes using `ps aux`
- Monitored real-time resource utilization via `top`
- Identified abnormal or unnecessary processes

**Security Impact:**  
Enables early detection of malicious or resource-abusive processes.

---

### 5. Service Hardening & Attack Surface Reduction
- Enumerated active services using `systemctl`
- Disabled unused or unnecessary services
- Ensured only required services remain active

**Security Impact:**  
Minimizes attack vectors by eliminating exposed services that could be exploited.

---

## OS Hardening Strategy
The following OS hardening controls were applied:
- Least privilege enforcement
- Service minimization
- Firewall-based network control
- Secure permission configurations
- Continuous system monitoring

These controls collectively strengthen the system’s security posture.

---

## Repository Artifacts
- `OS_Security_Checklist.md` – Verification checklist of applied security controls
- `README.md` – Detailed technical documentation
- `Screenshots/` – Evidence of configurations and command outputs

---

## Learning Outcomes
This task enhanced practical understanding of:
- Linux operating system security architecture
- Defensive security configurations
- Attack surface reduction techniques
- System-level controls used in real-world security environments

The knowledge gained is directly applicable to
**SOC operations, system hardening, penetration testing, and incident response**.

---

## Author
Cyber Security Intern

