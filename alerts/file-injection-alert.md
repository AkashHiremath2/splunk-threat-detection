# 🚨 File Injection / Path Traversal Alert

**Alert Name:** Suspicious File Access Attempt  
**Severity:** Medium  
**Trigger Type:** Real-time  
**Trigger Condition:** Any occurrence of known path injection patterns  
**SPL Used:** See `spl-queries/file-injection-detection.md`

---

## 🎯 Description

Triggers when users try to access system files or use `../` to escape directories.

---

## 🛠️ Suggested Actions

- Block IP
- Check for vulnerabilities in upload/download modules
- Review file permission settings
