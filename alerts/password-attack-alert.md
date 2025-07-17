# 🚨 Weak Password Usage Alert

**Alert Name:** Weak or Default Password Usage  
**Severity:** Medium  
**Trigger Type:** Real-time  
**Trigger Condition:** Successful login with a known weak/default password  
**SPL Used:** See `spl-queries/password-attack-patterns.md`

---

## 🎯 Description

Notifies if weak passwords like `admin`, `123456`, or `password` are used.

---

## 🛠️ Suggested Actions

- Force user to reset password
- Enforce strong password policy
- Audit password policies across systems
