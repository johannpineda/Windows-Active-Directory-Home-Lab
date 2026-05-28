# 🏢 Enterprise IT Infrastructure Home Lab
## Active Directory + Help Desk Ticketing System Simulation

<p align="center">
  <img src="assets/banner.jpg" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Active%20Directory-Windows%20Server-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/osTicket-Helpdesk-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Windows-10/11-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/VirtualBox-Lab-green?style=for-the-badge">
</p>

---

# 📌 Project Overview

This project simulates a **real-world enterprise IT environment**, combining:

- Windows Active Directory infrastructure
- Domain-joined client machines
- Group Policy management
- Enterprise Help Desk ticketing system (osTicket)
- Realistic IT troubleshooting workflows

It demonstrates skills required for:
- IT Support Specialist
- Desktop Support Technician
- Junior System Administrator
- SOC / Cybersecurity Analyst (foundation)

---

# 🏗️ Lab Architecture
```
                Internet (Simulated)
                       |
                       v
            +----------------------+
            |   pfSense (Optional) |
            | Firewall / Routing   |
            +----------------------+
                       |
    -----------------------------------------
    |                                       |
    v                                       v
    +--------------------+ +----------------------+
    | Windows Server | | Ubuntu Server |
    | Active Directory | | osTicket Help Desk |
    | DNS / DHCP / GPO | | Apache / MySQL / PHP |
    +--------------------+ +----------------------+
    |
    |
    +--------------------+ +--------------------+
    | Windows 10 Client | | Windows 11 Client |
    | Domain Joined PC | | Domain Joined PC |
    +--------------------+ +--------------------+
```

---

# 🧑‍💼 Active Directory Environment

## Features Implemented
- Domain Controller setup (Windows Server)
- Active Directory Domain Services (AD DS)
- Organizational Units (OU structure)
- User and group management
- Role-based access control
- Domain-joined client machines

## Group Policy (GPO)
- Password complexity enforcement
- Account lockout policies
- Desktop restrictions
- USB/device control policies
- Login/logout scripts

## File Sharing & Permissions
- Shared network drives
- NTFS permission structures
- Department-based access control

---

# 🎫 Help Desk Ticketing System (osTicket)

## Features Implemented
- Full osTicket deployment (Ubuntu Server)
- Ticket lifecycle management
- Department-based routing
- Agent assignment system
- SLA tracking

---

## 🧾 Ticket Scenarios (30+ Realistic Issues)

### 🔐 Authentication & Access
- Password resets
- Account lockouts
- MFA/login failures

### 🌐 Network Issues
- VPN connectivity failures
- DNS resolution issues
- Internet connectivity loss

### 🖥️ System Issues
- Slow computer performance
- Blue screen errors
- Windows update failures

### 🖨️ Hardware Issues
- Printer offline errors
- Peripheral device failures
- Monitor/display issues

### 📧 Application Issues
- Outlook not syncing
- Email delivery failures
- Software installation issues

### 🛡️ Security Issues
- Malware infections
- Phishing email reports
- Suspicious login attempts

---

# 🔧 Troubleshooting Documentation

Each ticket includes:

- Symptoms
- Root cause analysis
- Troubleshooting steps
- Resolution
- Escalation procedures
- Skills demonstrated

---

# 📁 Project Structure
```
enterprise-it-lab/
│
├── active-directory/
│ ├── setup-guide.md
│ ├── gpo-configs.md
│ └── user-management.md
│
├── helpdesk-system/
│ ├── osticket-setup.md
│ ├── ticket-examples/
│ └── workflows.md
│
├── tickets/
│ ├── vpn-issue.md
│ ├── dns-failure.md
│ ├── printer-issue.md
│ └── malware-response.md
│
├── screenshots/
│
├── architecture-diagram/
│
└── README.md
```

---


# 🧠 Skills Demonstrated

## IT Support
- Ticket management
- User support workflows
- Troubleshooting methodology

## System Administration
- Active Directory administration
- Group Policy configuration
- Windows Server management

## Networking
- DNS troubleshooting
- VPN connectivity
- Network diagnostics

## Security Fundamentals
- Malware response
- Account security
- Access control

## Documentation
- Incident reporting
- Root cause analysis
- IT process documentation

---

# 📸 Screenshots

- Active Directory Users & Computers
- Group Policy Management Console
- Domain-joined client machines
- osTicket dashboard
- Sample tickets (VPN, malware, printer, DNS)

---

# 🚀 Key Learning Outcomes

This project demonstrates:

- Real enterprise IT workflows
- End-to-end troubleshooting processes
- Identity and access management
- Help desk operations
- System administration fundamentals

---

# 🎯 Career Relevance

This lab directly maps to:

- IT Support Specialist
- Help Desk Technician
- Desktop Support Engineer
- Junior System Administrator
- SOC Analyst (foundation level)

---

# 💡 Why This Project Matters

This is not a tutorial lab — it is a **simulated enterprise IT environment**.

It demonstrates the ability to:
- manage users and systems
- troubleshoot real issues
- document incidents professionally
- operate within IT support workflows

---

# 🎥 Demo

👉 YouTube walkthrough: [Add Link Here]