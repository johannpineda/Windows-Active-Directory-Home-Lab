# 🔐 VPN Troubleshooting Guide

---

# 📌 Scenario

User unable to connect to corporate VPN remotely.

---

# 🛑 Symptoms

- VPN authentication failure
- “Unable to establish VPN connection”
- No access to internal resources
- Intermittent disconnects

---

# 🔎 Troubleshooting Steps

## 1. Verify Internet Connectivity

```powershell
ping google.com
```

---

## 2. Confirm VPN Client Status

Check:
- VPN application installed
- Client service running
- Latest updates applied

---

## 3. Validate User Credentials

- Reset password if needed
- Confirm MFA enrollment
- Verify account not locked

---

## 4. Test DNS Resolution

```powershell
nslookup company.local
```

---

## 5. Restart VPN Services

```powershell
ipconfig /flushdns
netsh winsock reset
```

---

# 🧠 Root Cause

Most VPN failures were caused by:
- expired credentials
- DNS issues
- outdated VPN client
- MFA sync problems

---

# ✅ Resolution

- Reset user password
- Reinstalled VPN client
- Flushed DNS cache
- Reconfigured MFA

---

# 🚨 Escalation Procedure

Escalate to:
- Network Team if tunnel unavailable
- Security Team for suspicious login activity