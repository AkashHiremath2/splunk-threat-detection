# 🛡️ XSS (Cross-Site Scripting) Attack Detection in Splunk

This query detects potential Cross-Site Scripting (XSS) attacks by searching for common XSS-related keywords in the logs collected from a host (`clientkali`).

---

## 🔍 SPL Query

```spl
index=* host=clientkali "<script" OR "javascript" OR "<img" OR "<body" OR "<a href"
