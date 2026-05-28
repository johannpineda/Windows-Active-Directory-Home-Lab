# 💻 Virtual Machine Configuration

---

# 🖥️ Virtual Machines Used

| VM | Purpose |
|---|---|
| Ubuntu Server | osTicket hosting |
| Windows 10 | End-user workstation |

---

# ⚙️ Recommended Specs

## Ubuntu Server

- 2 CPU
- 4 GB RAM
- 40 GB Storage

---

## Windows 10

- 2 CPU
- 8 GB RAM
- 60 GB Storage

---

# 🌐 Network Configuration

Use:
- NAT Adapter
or
- Bridged Adapter

---

# 🔗 Connectivity Testing

```powershell
ping SERVER-IP
```

---

# 📁 Shared Folder Setup

Enable:
- bidirectional clipboard
- drag-and-drop
- shared folders

---

# 🔐 Security Recommendations

- Enable Windows Defender
- Keep systems updated
- Use strong passwords
- Snapshot VMs regularly

---

# 📸 Snapshot Strategy

Create snapshots:
- Before malware testing
- Before major configuration changes
- Before software installation

---

# ✅ Final Validation

Verify:
- osTicket accessible
- tickets functioning
- email notifications working
- client VM connectivity operational