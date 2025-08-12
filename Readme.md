# IT Infrastructure Lab — AWS & Active Directory

This repository contains hands-on lab projects demonstrating **real-world IT administration tasks** across AWS and Windows Active Directory environments.  
All labs are documented step-by-step with **screenshots, scripts, and configurations** to showcase practical skills for system administration, networking, and cloud operations.

---

## 📂 Lab Contents

| Folder | Description |
|--------|-------------|
| **AWS-EC2-Instance-Creating** | Launching and configuring an AWS EC2 instance, including key pair generation, security groups, and instance connection methods. |
| **Group-Created-&-Added-to-GPO** | Creation of security groups in Active Directory and linking them to Group Policy Objects for permissions and policy enforcement. |
| **Organizational-Unit-Created** | Designing and creating OUs to organize users, computers, and groups within Active Directory. |
| **Creating-Users** | Step-by-step creation of domain users with security best practices, including password settings and account permissions. |
| **Disable_USB_GPO** | Implementing and testing a Group Policy Object to disable USB storage devices across domain-joined computers. |
| **Active-Directory-Installation-&-Promoting** | Installing the AD DS role, promoting a server to a Domain Controller, creating a forest/domain, and verifying DNS/SRV records. |
| **Git-Initialized** | Initial Git setup for the lab repository, including `.gitignore` and first commits. |

---

## 🖼️ Screenshots
Screenshots for each lab are available in their respective folders. Examples include:
- ADUC with OUs, users, and groups created.
- AWS EC2 dashboard and SSH/RDP connection tests.
- Group Policy Management Console showing linked GPOs.
- Command outputs: `gpresult`, `nslookup`, `dcdiag`.

---

## 🛠️ Skills Demonstrated
- AWS EC2 provisioning and basic networking
- Active Directory installation, configuration, and management
- Group Policy Object creation and enforcement
- Organizational Unit design and delegation
- User and group account management
- Windows DNS and SRV record verification
- Git version control for documentation and scripts

---

## 🚀 How to Use This Repo
1. Clone the repository:
   ```bash
   git clone https://github.com/jaysomwanshi/active-directory-ldap-lab.git
