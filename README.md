# OWASP Cyber Training

### Objectives
- What are the OWASP Top 10
- Identify/explain some common security vulnerabilities
- Fix some common security vulnerabilities
- Discuss security best practices

## OWASP
- What is it?
- OWASP top 10

## Identifying Vectors
- Categorising vectors
  - [Chance vs Impact](https://raw.githubusercontent.com/iO-Academy/pen-testing/main/risk.png)

## Attack Vectors
- Vulnerability chains

### Low Risk
- Sensitive Data Exposure (Security Misconfiguration)
  - Static files: `README.md`, `robots.txt`, `composer.json`, `package.json`, `.git`
  - Familiar/common URLs: WP Login
  - Source code review
    - EXERCISE - Source Code Review
  - Cookies
  - Error messages/default error pages
- Incorrect HTTP request types (Security Misconfiguration)
  - EXERCISE - Incorrect HTTP Request types
- Directory Traversal (Security Misconfiguration)
  - EXERCISE - Directory Traversal
   
### Medium Risk
- Logging (Security Logging and Monitoring Failures)
  - EXERCISE - Logging
- Logic Flaws (Broken Access Control)
  - EXERCISE - Logic Flaws
- Validation (Insecure Design)
  - Client Side
    - EXERCISE - Validation
- XSS (Injection)
  - Reflected
  - Stored
  - Preventing XSS
    - EXERCISE - XSS

### High Risk
- Third Party Libraries (Vulnerable and Outdated Components)
  - [Read this](https://david-gilbertson.medium.com/im-harvesting-credit-card-numbers-and-passwords-from-your-site-here-s-how-9a8cb347c5b5)
- SQL Injection (Injection)
  - Exploiting it
  - Protecting against it
  - EXERCISES - SQL Injection Collection
- Command Injection (Injection)
  - EXERCISE - Command Injection
- CSRF & SSRF (Server-Side Request Forgery)

### Extras
- Server Side Template Injection (Injection)
  - EXERCISE - SSTI
- XXE (Security Miconfiguration)
  - EXERCISE - XXE collection

### Additional Practice
- [Hack your First Web App collection](https://immersivelabs.online/series/hack-your-first-web-application/labs)

 
  
