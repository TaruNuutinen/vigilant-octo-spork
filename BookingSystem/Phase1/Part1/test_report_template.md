# 1️⃣ Introduction

**Tester:**  
- Name: Taru Nuutinen 

**Purpose:**  
- Testing user registration functionality and identify as many anomalies and vulnerabilities as possible in this area. And after that categorizing findings.

**Scope:**  
- Tested components: Registration
- Exclusions: DoS
- Test approach: Grey-box

**Test environment & dates:**  
- Start: 17:30 21.11.2025
- End: 17:50 21.11.2025
- Test environment details (OS, runtime, DB, browsers): -Debian GNU/Linux 13 (trixie), -Deno 2.5.6 (JavaScript/TypeScript), -PostgreSQL, -Firefox 145 (via ZAP Selenium integration) and Chrome 142 (via ZAP Selenium integration)

**Assumptions & constraints:**  
- Test executed in isolated enviroment, Performed with OWASP ZAP, System is being developed in phases and testing the first phase, Limited time (2 weeks), Resource constraint: only one tester, no team

---

# 2️⃣ Executive Summary

**Short summary (1-2 sentences):**  
- First web-page penetration testing round, testing registration and finding vulnerabilities and anomalies. Using docker and OWASP ZAP.

**Overall risk level:** High

**Top 5 immediate actions:**  
1.  Apply all avaible patches to critical vulnerabilities
2.  Enforce strict input validation, adopt an allow list strategy.
3.  Apply stringent rules for filenames and paths. 
4.  Use parameterized queries
5.  Apply least privilege in database access as possible

---

# 3️⃣ Severity scale & definitions

|  **Severity Level**  | **Description**                                                                                                              | **Recommended Action**           |
| -------------------- | ---------------------------------------------------------------------------------------------------------------------------- | -------------------------------- |
|      🔴 **High**     | A serious vulnerability that can lead to full system compromise or data breach (e.g., SQL Injection, Remote Code Execution). | *Immediate fix required*         |
|     🟠 **Medium**    | A significant issue that may require specific conditions or user interaction (e.g., XSS, CSRF).                              | *Fix ASAP*                       |
|      🟡 **Low**      | A minor issue or configuration weakness (e.g., server version disclosure).                                                   | *Fix soon*                       |
| 🔵 **Info** | No direct risk, but useful for system hardening (e.g., missing security headers).                                            | *Monitor and fix in maintenance* |


---

# 4️⃣ Findings (filled with examples → replace)

> Fill in one row per finding. Focus on clarity and the most important issues.

| ID | Severity | Finding | Description | Evidence / Proof |
|------|-----------|----------|--------------|------------------|
| F-01 | 🔴 High | SQL Injection in registration | Input field allows `' OR '1'='1` injection | Screenshot or sqlmap result |
| F-02 | 🔴 High | Path Traversal | To access files or execute commands anywhere on the file-system, Path Traversal attacks will utilize the ability of special-characters sequences. | Screenshot or Burp log |
| F-03 | 🟠 Medium | Session fixation | Session ID remains unchanged after login | Burp log or response headers |
| F-04 | 🟡 Low | Weak password policy | Accepts passwords like "12345" | Screenshot of registration success |

---

> [!NOTE]
> Include up to 5 findings total.   
> Keep each description short and clear.

---

# 5️⃣ OWASP ZAP Test Report (Attachment)

**Purpose:**  
- Attach or link your OWASP ZAP scan results (Markdown format preferred).

---

**Instructions (CMD version):**
1. Run OWASP ZAP baseline scan:  
   ```bash
   zap-baseline.py -t https://example.com -r zap_report_round1.html -J zap_report.json
   ```
2. Export results to markdown:  
   ```bash
   zap-cli report -o zap_report_round1.md -f markdown
   ```
3. Save the report as `zap_report_round1.md` and link it below.

---
> [!NOTE]
> 📁 **Attach full report:** → `check itslearning` → **Add a link here**

---
