# 🛡️ SQL Injection Attack Detection in Splunk

This query is designed to detect potential SQL Injection (SQLi) attempts by searching for common SQLi keywords and patterns in logs, especially within URL parameters and request payloads.

---

## 🔍 SPL Query

```spl
index=* host=clientkali "' OR 1=1" OR "'--" OR "' OR '1'='1" OR "UNION SELECT" OR "xp_cmdshell" OR "OR 1=1--" OR "SELECT" OR "FROM"
