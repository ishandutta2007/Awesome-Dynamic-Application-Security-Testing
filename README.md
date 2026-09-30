# Awesome-Dynamic-Application-Security-Testing

## Top Dynamic Application Security Testing (DAST) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Runtime Vulnerability Scanning, API Security Testing & CI/CD Integration*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Dynamic Application Security Testing (DAST)**. These tools test running web applications and APIs for security vulnerabilities by simulating attacks from the outside, identifying issues like SQL injection, XSS, and misconfigurations that static analysis cannot detect.



**Examples** include Invicti, Acunetix, Burp Suite Enterprise, Rapid7 InsightAppSec, HCL AppScan, Detectify, Probely, StackHawk, OWASP ZAP, Intruder, Veracode DAST, and Checkmarx DAST (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom scanning logic, and transparent security testing — ideal for DevSecOps teams, security engineers, and developers building vendor-independent DAST pipelines. The open-source ecosystem is anchored by **OWASP ZAP** (the de-facto standard) and **Nuclei** (template-driven scanning), with strong coverage in specialized scanners for XSS, SQLi, and modern SPA frameworks.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Invicti](https://www.invicti.com/)**  

  Enterprise DAST platform with proof-based scanning that virtually eliminates false positives. Parallel crawling engine maps large applications faster than sequential scanners, with built-in login recorder and asset discovery. Integrates with Jira, Azure DevOps, and GitLab Issues for automated ticket creation .



- **[Acunetix](https://www.acunetix.com/)**  

  Commercial web vulnerability scanner with built-in scanning policies covering OWASP Top Ten. Supports authenticated scans via Selenium-based login scripting for complex multi-step authentication flows .



- **[Burp Suite Enterprise](https://portswigger.net/burp/enterprise)**  

  Enterprise-grade DAST platform from PortSwigger with comprehensive manual testing capabilities and automated scanning. The community edition is free with limited functionality; enterprise adds scheduling, CI/CD integration, and team collaboration.



- **[Rapid7 InsightAppSec](https://www.rapid7.com/products/insightappsec/)**  

  Cloud-based DAST platform with automated crawling and attack simulation. Integrates with CI/CD pipelines and provides detailed remediation guidance.



- **[HCL AppScan](https://www.hcltechsw.com/appscan)**  

  Enterprise application security testing suite with DAST capabilities for web applications and APIs.



- **[Detectify](https://detectify.com/)**  

  Automated external attack surface monitoring and DAST platform with continuous scanning and remediation guidance.



- **[Probely](https://probely.com/)**  

  DAST platform designed for developers with API-first architecture, CI/CD integration, and actionable vulnerability reports.



- **[StackHawk](https://www.stackhawk.com/)**  

  API-focused DAST platform with free tier for open-source projects. Recent releases include JSON-RPC scanning, Modern AJAX Spider for SPA frameworks, DOM XSS sink detection, and Chrome/Puppeteer-based browser automation .



- **[OWASP ZAP](https://www.zaproxy.org/)**  

  The reference open-source DAST tool, now maintained by Checkmarx. Functions as an intercepting proxy with active/passive scanning, API testing, and CI/CD integration. Available as GUI, CLI, and Docker. Supports OpenAPI, GraphQL, and SOAP API documentation import .



- **[Intruder](https://www.intruder.io/)**  

  Cloud-based vulnerability scanner with automated DAST and external attack surface monitoring.



- **[Veracode DAST](https://www.veracode.com/)**  

  Enterprise DAST integrated with Veracode's application security platform, supporting web apps and APIs.



- **[Checkmarx DAST](https://checkmarx.com/)**  

  DAST solution integrated with Checkmarx's broader AppSec platform, now the maintainer of OWASP ZAP .



## Open-Source GitHub Projects



- **[OWASP ZAP](https://github.com/zaproxy/zaproxy)**  

  The most widely used open-source DAST tool by GitHub stars, covering automated vulnerability scanning, manual penetration testing, and REST API testing . Functions as a transparent proxy intercepting traffic between browser and web application for real-time analysis. Added first-phase integration with the OWASP PenTest Kit (PTK) browser extension, pre-installed in ZAP-launched browsers, enabling authenticated-session testing for single-page applications . Community-maintained with broad add-on ecosystem and documentation. Apache-2.0 licensed .



- **[Nuclei](https://github.com/projectdiscovery/nuclei)**  

  Template-driven security scanning framework with 30,000+ GitHub stars. Each check is a YAML file describing request, matcher, and expected response. Community maintains thousands of templates covering CVEs, misconfigurations, default credentials, and exposed panels . Scans faster than crawling-based tools by targeting known vulnerability patterns directly. Supports workflows chaining templates for technology-specific scanning, multiple protocols (HTTP, DNS, TCP), headless browser interactions, and SARIF output for GitHub code scanning . **Trade-off**: Cannot discover application-specific vulnerabilities like business logic flaws or custom injection points — excels at checking whether known issues exist, not finding novel ones .



- **[Wapiti](https://github.com/wapiti-scanner/wapiti)**  

  Black-box web vulnerability scanner that crawls deployed applications, extracts links/forms/scripts, and injects payloads into discovered parameters to detect abnormal behavior indicating vulnerabilities . Supports passive mode for traffic analysis without active fuzzing. Custom scripting extends detection capabilities for specialized environments . Command-line only.



- **[Nikto](https://github.com/sullo/nikto)**  

  Open-source web server scanner testing for dangerous files/CGIs, outdated server software, and misconfigurations. Command-line only with no GUI . Recent updates include faster scans, new DSL for defining checks, randomized User-Agent to reduce fingerprinting, and rewritten LFI testing module. License changed to GPLv3 .



- **[XSStrike](https://github.com/s0md3v/XSStrike)**  

  Specialized DAST scanner focused exclusively on cross-site scripting (XSS) vulnerabilities. Analyzes HTTP parameters and DOM structures to identify reflected, stored, and blind injection points .



- **[Dalfox](https://github.com/hahwul/dalfox)**  

  Automated XSS vulnerability scanner with payload mutation engine and WAF evasion strategies. Provides Model Context Protocol (MCP) server and REST API for programmatic scanning by AI agents .



- **[SQLmap](https://github.com/sqlmapproject/sqlmap)**  

  Automated SQL injection detection and exploitation suite. Sends malicious payloads and analyzes responses to detect database vulnerabilities. Sophisticated dynamic payload adaptation and heuristic engine . **Focused DAST scanner** for database flaws — does not cover other vulnerability types .



- **[WPScan](https://github.com/wpscanteam/wpscan)**  

  Free for non-commercial use, WordPress-specific vulnerability scanner. Identifies security issues in WordPress core, themes, and plugins through black-box scanning and component enumeration. Regularly updated vulnerability database . **Limited to WordPress applications** .



- **[Gung12](https://github.com/DenReanin/gung12)**  

  Python-based DAST specializing in web form vulnerabilities. Covers 12 OWASP-aligned categories: XSS, SQLi, SSTI, XPath, CMDi, NoSQL, XXE, CSRF, File Upload, Open Redirect, HTML Injection, Logic . Features blind SQLi (boolean and time-based) with differential confirmation, semantic Command Injection confirmation, GraphQL mode, WebSocket mode, gRPC reflection detection, SPA support with Playwright, WAF bypass, CSRF token refresh, and SARIF 2.1.0 output for GitHub Code Scanning . Low false positive rate through semantic evidence confirmation .



- **[DORM](https://github.com/MrEx-Right/DORM)**  

  High-performance concurrent vulnerability scanner written in Go for red teams and bug bounty hunters. Features native DAST proxy, smart spider with active fuzzing, offline NIST CVE database (280,000+ records), multi-phase injection pipelines (Omni-SQLi, Blind RCE, XXE, SSRF, SSTI, CRLF), authentication testing (brute force, JWT algorithm confusion, IDOR, GraphQL introspection), cloud service exposure detection, AI/LLM infrastructure scanning, and WAF evasion . Web dashboard with real-time SSE monitoring and HTML/PDF reporting .



- **[justdastit](https://github.com/SnailSploit/justdastit)**  

  Open-source CLI DAST toolkit positioned as "The Burp You Can Afford" . Features active scanning (reflected XSS, SQLi, SSTI, path traversal, command injection, open redirect), passive checks (missing security headers, CORS misconfig, sensitive data exposure), intercepting proxy, repeater, decoder/encoder/hasher, and report generation (HTML/JSON) . Interactive REPL shell, config generator, and history/findings/sitemap management .



- **[ProofCMS](https://github.com/pxawtyy/proofcms)**  

  Modular Python toolkit for detecting WordPress/Joomla vulnerabilities with explicit evidence, false-positive controls, and CI-friendly reports. Passive, safe, and isolated-lab verification modes distinguish successful PHP execution from source-code disclosure . Active verification disabled by default, requires explicit authorization flags .



### Additional Strong Open-Source Options



- **Arachni** — Modular design and advanced crawling capabilities were notable, but project is **obsolete** (last release 2022) . Treat as end-of-life; use ZAP or Wapiti as replacements.

- **OpenVAS** — Primarily a network/host vulnerability scanner, not web application DAST. Belongs as adjacent tool for host/network coverage .

- **Lonkero** — High-performance web vulnerability scanner in Rust for penetration testers, focused on reducing false positives .

- **Nmap** — Network mapper for initial reconnaissance, identifying open ports, services, and web server versions. Not a web app vulnerability scanner itself .

- **w3af** — Web application attack and audit framework .



**Frameworks for building custom DAST pipelines**: Combine **OWASP ZAP** for comprehensive crawling and scanning as the default foundation . Use **Nuclei** for fast, template-driven checks against known vulnerability patterns and custom detection logic . Integrate **Gung12** for form-focused scanning with SARIF output for CI/CD . Deploy **DORM** for aggressive red-team-focused scanning with offline CVE correlation . For specialized needs, **XSStrike** or **Dalfox** for XSS, **SQLmap** for SQLi, and **WPScan** for WordPress . Note that open-source DAST requires significant tuning for modern SPAs and complex authentication, and lacks vendor support — but provides capable dynamic testing at zero license cost .



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- DAST tools must be used only against systems you own or are explicitly authorized to test. Unauthorized scanning may violate computer fraud laws.

- Self-hosted open-source solutions require proper infrastructure, tuning for modern frameworks (SPAs, GraphQL), and ongoing maintenance. Automated scanning produces false positives — results require human validation .

- Open-source DAST lacks vendor support and enterprise features like asset discovery, proof-based scanning, and compliance reporting. Evaluate gaps before relying on them for regulatory requirements.



---



**Made for security engineers, DevSecOps teams, penetration testers, and application security professionals.**  

Let's make dynamic application security testing more open, transparent, and effective.
