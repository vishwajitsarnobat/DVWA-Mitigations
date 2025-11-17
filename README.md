# Web Security Vulnerability Analysis

This repository contains supplementary materials for the "Experiment No. 7 - Experiment on Web Security" project. The project involves the identification, exploitation, and remediation of common web application vulnerabilities using the Damn Vulnerable Web Application (DVWA).

## Repository Contents

*   `codes/`: Contains scripts used to demonstrate vulnerabilities.
    *   `csrf-attack.html`: A proof-of-concept HTML file to execute a Cross-Site Request Forgery (CSRF) attack that changes a user's password.
    *   `shell.php`: A simple PHP web shell used to achieve Remote Code Execution via the File Upload vulnerability.
*   `docs/`: Contains code snippets and patches applied to the DVWA source to mitigate identified vulnerabilities, including SQL Injection and Command Injection. The complete analysis, including detailed methodology, root cause analysis, risk assessment, and lessons learned, is documented in the PDF report submitted as the primary deliverable for this experiment.


## Technology Stack

*   **Environment:** Damn Vulnerable Web Application (DVWA)
*   **Stack:** LAMP (Linux, Apache2, MariaDB, PHP)
*   **Tools:** Burp Suite Community Edition
