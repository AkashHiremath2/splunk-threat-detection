# 🚨 XSS Detection Alert

**Alert Name:** Possible XSS Attack Detected  
**Severity:** High  
**Trigger Type:** Real-time  
**Trigger Condition:** If search matches XSS keywords from same IP 3+ times in 5 mins  
**SPL Used:** See `spl-queries/xss-detection.md`

---

## 🎯 Description

This alert detects repeated injection of suspicious HTML/JS tags like `<script>`, `<img>`, and `javascript` in web requests — potential signs of Cross-Site Scripting (XSS) attacks.

---

## 🛠️ Suggested Actions

- Investigate user input fields in web app
- Block offending IP via WAF
- Monitor affected endpoint for further abuse
