# 🚨 Dictionary Attack Alert

**Alert Name:** Credential Stuffing Attempt  
**Severity:** High  
**Trigger Type:** Real-time  
**Trigger Condition:** More than 10 login failures in 10 minutes from same IP  
**SPL Used:** See `spl-queries/dictionary-attack.md`

---

## 🎯 Description

Attackers may be trying many different passwords against the same account or system.

---

## 🛠️ Suggested Actions

- Monitor IP for multiple targets
- Add it to blocklist or firewall
- Recommend password reset if account compromised
