# 🚨 Failed Login Alert

**Alert Name:** Brute Force Login Attempt  
**Severity:** High  
**Trigger Type:** Real-time  
**Trigger Condition:** More than 5 failed login attempts from one user/IP within 10 minutes  
**SPL Used:** See `spl-queries/failed-logins.md`

---

## 🎯 Description

Indicates potential brute force attack using repeated login failures.

---

## 🛠️ Suggested Actions

- Block or temporarily lock account
- Investigate IP
- Enable rate-limiting or MFA
