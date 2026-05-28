# 🖨️ Printer Offline Troubleshooting

---

# 📌 Scenario

User unable to print to network printer.

---

# 🛑 Symptoms

- Printer status shows Offline
- Print queue stuck
- Unable to discover printer

---

# 🔎 Troubleshooting Steps

## 1. Verify Printer Connectivity

Check:
- power status
- ethernet/Wi-Fi connection
- printer display errors

---

## 2. Restart Print Spooler

```powershell
net stop spooler
net start spooler
```

---

## 3. Clear Print Queue

```powershell
del %systemroot%\System32\spool\printers\* /Q
```

---

## 4. Reinstall Printer Driver

- Remove device
- Install latest manufacturer driver

---

## 5. Test Network Reachability

```powershell
ping PRINTER-IP
```

---

# 🧠 Root Cause

Common causes:
- spooler service failure
- stale print jobs
- driver corruption
- network interruption

---

# ✅ Resolution

- Restarted spooler
- Cleared stuck jobs
- Reinstalled drivers

---

# 🚨 Escalation Procedure

Escalate if:
- hardware failure suspected
- printer inaccessible to multiple users
- recurring spooler crashes occur