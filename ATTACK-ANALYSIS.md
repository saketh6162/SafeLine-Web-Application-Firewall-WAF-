# 🔍 SQL Injection Analysis

## Attack Payload

`1' OR '1'='1`

## Attack Explanation

This payload alters SQL query logic to always evaluate as true, allowing unauthorized access.

## Without WAF

* Application returned all user data
* Authentication bypass successful

## With WAF

* Request detected as malicious
* Blocked before reaching backend

## Evidence

* SafeLine dashboard shows blocked threats
* Logs confirm SQL Injection detection

## Conclusion

WAF protects applications by inspecting HTTP requests and blocking malicious patterns like SQL Injection.
