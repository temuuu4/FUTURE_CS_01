# FUTURE_CS_01
# Vulnerability Assessment Report – demo.testfire.net

##  Objective
This project involves performing a vulnerability assessment on a public web application using passive security testing techniques.

##  Target
demo.testfire.net

##  Scope
- Public-facing pages only
- No exploitation performed
- Passive analysis only

##  Tools Used
- Nmap (Port Scanning)
- OWASP ZAP (Passive Scan)
- Browser DevTools (Headers & Cookies)

##  Key Findings
- Missing Content Security Policy (CSP)
- Missing Anti-Clickjacking Protection
- Cookie without proper SameSite restriction
- Server Information Disclosure
- Missing HSTS Header
- Open Network Ports
- Missing Security Headers

## 📊 Risk Summary
- Medium Risk: Multiple issues identified
- Low Risk: Configuration-related issues

##  Project Structure
- `/Report` → Final PDF report
- `/Screenshots` → Evidence from tools

##  Note
This assessment was conducted ethically using passive techniques only, without exploiting any vulnerabilities.
