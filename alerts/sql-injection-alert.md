# 🚨 SQL Injection Detection Alert

**Alert Name:** Possible SQL Injection Attempt  
**Severity:** Critical  
**Trigger Type:** Real-time  
**Trigger Condition:** If same IP triggers SQLi keywords more than 2 times in 5 minutes  
**SPL Used:** See `spl-queries/sql-injection-detection.md`

---

## 🎯 Description

Detects patterns like `' OR 1=1 --`, `UNION SELECT`, and `xp_cmdshell` — known SQL injection payloads in query strings.

---

## 🛠️ Suggested Actions

- Block IP address
- Perform vulnerability testing on affected endpoint
- Patch and sanitize SQL inputs
