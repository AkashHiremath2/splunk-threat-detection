# 🛡️ File Injection Attack Detection in Splunk

Detects attempts to access sensitive system files or exploit directory traversal vulnerabilities via HTTP requests.

---

## 🔍 SPL Query

```spl
index=* host=clientkali "/etc/passwd" OR "../" OR "..\\" OR "boot.ini" OR "C:\\Windows\\System32"
