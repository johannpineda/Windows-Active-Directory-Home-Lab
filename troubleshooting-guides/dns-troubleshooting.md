# 🌐 DNS Troubleshooting Guide

---

# 📌 Scenario

User can access some websites but cannot reach internal company resources.

---

# 🛑 Symptoms

- “DNS server not responding”
- Websites fail to load
- VPN connected but resources inaccessible

---

# 🔎 Troubleshooting Steps

## 1. Check IP Configuration

```powershell
ipconfig /all
```

---

## 2. Test Connectivity

```powershell
ping 8.8.8.8
```

---

## 3. Verify DNS Resolution

```powershell
nslookup google.com
```

---

## 4. Flush DNS Cache

```powershell
ipconfig /flushdns
```

---

## 5. Restart Network Adapter

```powershell
netsh interface set interface "Wi-Fi" disable
netsh interface set interface "Wi-Fi" enable
```

---

# 🧠 Root Cause

Issue caused by:
- corrupted DNS cache
- incorrect DNS settings
- ISP DNS outage

---

# ✅ Resolution

- Updated DNS server addresses
- Flushed DNS cache
- Restarted network adapter

---

# 🚨 Escalation Procedure

Escalate to Network Team if:
- multiple users affected
- DNS server unavailable
- corporate domain unreachable