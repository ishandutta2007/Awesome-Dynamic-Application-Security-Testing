<p align="center">
  <img src="assets/banner.svg" alt="Awesome Dynamic Application Security Testing Banner" width="100%" />
</p>

# 🛡️ Awesome Dynamic Application Security Testing (DAST) [![Awesome](https://awesome.re/badge.svg)](https://github.com/ishandutta2007/Awesome-Awesome-Awesome)

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Dynamic-Application-Security-Testing"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Dynamic-Application-Security-Testing?style=social" alt="Stars"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

> **A curated, SEO-optimized list of top Dynamic Application Security Testing (DAST) SaaS platforms, open-source vulnerability scanners, runtime security tools, and DevSecOps integrations.**

---

## 💡 Overview & Market Landscape

The global **Dynamic Application Security Testing (DAST)** market is a critical pillar of Application Security Testing (AST), valued at approximately **\$1.44 Billion USD** (growing at ~26.7% CAGR). 

The sector is **moderately fragmented**: 
- **Enterprise Heavyweights & Conglomerates** (e.g., HCLTech, Veracode, Checkmarx, Invicti) control large enterprise compliance and legacy application security budgets.
- **Developer-Centric & Niche Innovators** (e.g., StackHawk, Detectify, Probely, Intruder) captured fast-growing mid-market and CI/CD pipeline automation segments.
- **Open-Source Standard Bearers** (e.g., OWASP ZAP, Nuclei, SQLmap) drive vendor-independent security auditing across global security research and engineering teams.

---

## 📋 Table of Contents

- [🏢 SaaS & Hosted DAST Platforms](#-saas--hosted-dast-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ Additional Specialized Options](#️-additional-specialized-options)
- [🤝 How to Contribute](#-how-to-contribute)
- [💖 Support & Sponsorship](#-support--sponsorship)
- [📈 Star History](#-star-history)
- [⚠️ Disclaimer](#️-disclaimer)

---

## 🏢 SaaS & Hosted DAST Platforms

Below is a comparative breakdown of commercial DAST SaaS solutions, sorted by **Company Size / Revenue / Valuation** (descending).

| SaaS Platform | Company Size / Valuation / Revenue | Starting Pricing | Free Tier / Free Trial Limit | Core DAST Strengths |
| :--- | :--- | :--- | :--- | :--- |
| **[HCL AppScan](https://www.hcltechsw.com/appscan)** | **~$13.3 Billion** *(HCLTech Enterprise)* | ~$2,500 / year (Custom Enterprise quote) | 30-Day Free Trial (Full DAST evaluation) | Enterprise AppSec suite for complex web applications and legacy API portfolios. |
| **[Veracode DAST](https://www.veracode.com/)** | **~$2.5 Billion** *(Valuation / TA Associates)* | ~$10,000 / year (Base module quote) | 14-Day Free Trial / Custom Enterprise POC | Integrated cloud DAST platform with unified SAST, SCA, and compliance analytics. |
| **[Checkmarx DAST](https://checkmarx.com/)** | **~$1.15 Billion** *(Acquired by Hellman & Friedman)* | ~$8,000 / year (Custom Enterprise quote) | Guided Enterprise Demo (No self-serve trial) | Scalable enterprise scanner built around checkmarx AppSec platform & ZAP engine. |
| **[Rapid7 InsightAppSec](https://www.rapid7.com/products/insightappsec/)** | **~$2.0 Billion** *(Public: RPD)* | ~$2,000 / app / year | 30-Day Free Trial | Automated attack simulation and continuous cloud vulnerability scanning. |
| **[Invicti](https://www.invicti.com/)** | **~$1.0 Billion** *(Valuation / ~$100M+ ARR)* | ~$7,000 / year | 14-Day Enterprise Demo / Trial on Request | Proof-based scanning eliminating false positives with interactive login recorder. |
| **[Detectify](https://detectify.com/)** | **~$85M Valuation** stroke="white" (~$15M ARR) | $85 / month (Surface plan) | 14-Day Free Trial (Unlimited external surface mapping) | Continuous external attack surface monitoring and automated payload scanning. |
| **[StackHawk](https://www.stackhawk.com/)** | **~$50.2M Raised** (~$5M ARR) | $39 / contributor / month | 14-Day Free Trial (Includes 10 cloud scan hours) | Developer-first API scanning with REST, GraphQL, JSON-RPC & CI/CD pipeline focus. |
| **[Probely](https://probely.com/)** | **~$12M Raised** (Acquired by Snyk) | €49 / month | 14-Day Free Trial (Full vulnerability scanner features) | API-first web scanner with actionable developer remediation guides & Jira sync. |
| **[Burp Suite Enterprise](https://portswigger.net/burp/enterprise)** | **~$35M ARR** *(PortSwigger Private)* | $475 / user / year (Pro) / $6,360/yr (Enterprise) | 14-Day Free Trial (Burp Suite Enterprise Agent) | Industry standard penetration testing scanner engine scaled for scheduled CI/CD scans. |
| **[Intruder](https://www.intruder.io/)** | **~$2.5M ARR** | $113 / month | Free Tier Available (Limited Exposure) / 14-Day Full Trial | Automated cloud perimeter scanning and attack surface vulnerability management. |
| **[Acunetix](https://www.acunetix.com/)** | **Part of Invicti Group** | ~$4,500 / year | 14-Day Demo / Trial on Request | Advanced multi-step authentication scanning with built-in OWASP Top 10 policies. |

---

## 🔓 Open-Source GitHub Projects

Curated open-source DAST tools, active scanners, and specialized security frameworks. Sorted by **GitHub Star Count** (descending).

| Project & Repo | Star Count | Primary Focus & Features | License |
| :--- | :--- | :--- | :--- |
| **[sqlmap](https://github.com/sqlmapproject/sqlmap)** | [<img src="https://img.shields.io/github/stars/sqlmapproject/sqlmap?style=social&color=white" alt="sqlmap stars"/>](https://github.com/sqlmapproject/sqlmap/stargazers) | Automated SQL injection detection, database takeover, and dynamic payload adaptation engine. | GPL-2.0 |
| **[Nuclei](https://github.com/projectdiscovery/nuclei)** | [<img src="https://img.shields.io/github/stars/projectdiscovery/nuclei?style=social&color=white" alt="nuclei stars"/>](https://github.com/projectdiscovery/nuclei/stargazers) | Fast, template-driven vulnerability scanner for web apps, APIs, DNS, and headless browser checks. | MIT |
| **[OWASP ZAP](https://github.com/zaproxy/zaproxy)** | [<img src="https://img.shields.io/github/stars/zaproxy/zaproxy?style=social&color=white" alt="ZAP stars"/>](https://github.com/zaproxy/zaproxy/stargazers) | De-facto open-source DAST proxy & vulnerability scanner with active/passive checks, OpenAPI & GraphQL support. | Apache-2.0 |
| **[Nikto](https://github.com/sullo/nikto)** | [<img src="https://img.shields.io/github/stars/sullo/nikto?style=social&color=white" alt="nikto stars"/>](https://github.com/sullo/nikto/stargazers) | Command-line web server scanner checking for dangerous CGIs, outdated software, and misconfigurations. | GPL-3.0 |
| **[XSStrike](https://github.com/s0md3v/XSStrike)** | [<img src="https://img.shields.io/github/stars/s0md3v/XSStrike?style=social&color=white" alt="XSStrike stars"/>](https://github.com/s0md3v/XSStrike/stargazers) | Advanced XSS detection suite with payload generator, DOM parser, and intelligent fuzzing engine. | GPL-3.0 |
| **[WPScan](https://github.com/wpscanteam/wpscan)** | [<img src="https://img.shields.io/github/stars/wpscanteam/wpscan?style=social&color=white" alt="WPScan stars"/>](https://github.com/wpscanteam/wpscan/stargazers) | Black-box WordPress security scanner enumerating plugins, themes, and known core vulnerabilities. | Custom / Non-Comm |
| **[Dalfox](https://github.com/hahwul/dalfox)** | [<img src="https://img.shields.io/github/stars/hahwul/dalfox?style=social&color=white" alt="dalfox stars"/>](https://github.com/hahwul/dalfox/stargazers) | Fast parameter analysis and XSS scanner written in Go with MCP server for AI agent integrations. | MIT |
| **[Wapiti](https://github.com/wapiti-scanner/wapiti)** | [<img src="https://img.shields.io/github/stars/wapiti-scanner/wapiti?style=social&color=white" alt="wapiti stars"/>](https://github.com/wapiti-scanner/wapiti/stargazers) | Black-box web scanner auditing forms, scripts, payload injections, and passive traffic analysis. | GPL-3.0 |
| **[DORM](https://github.com/MrEx-Right/DORM)** | [<img src="https://img.shields.io/github/stars/MrEx-Right/DORM?style=social&color=white" alt="DORM stars"/>](https://github.com/MrEx-Right/DORM/stargazers) | Concurrent Go-based DAST scanner featuring active fuzzing proxy, NIST CVE correlation, and LLM scans. | AGPL-3.0 |
| **[Gung12](https://github.com/DenReanin/gung12)** | [<img src="https://img.shields.io/github/stars/DenReanin/gung12?style=social&color=white" alt="gung12 stars"/>](https://github.com/DenReanin/gung12/stargazers) | OWASP-aligned web form DAST scanner with Playwright SPA support, blind injection confirmation, and SARIF output. | MIT |
| **[justdastit](https://github.com/SnailSploit/justdastit)** | [<img src="https://img.shields.io/github/stars/SnailSploit/justdastit?style=social&color=white" alt="justdastit stars"/>](https://github.com/SnailSploit/justdastit/stargazers) | Interactive CLI DAST toolkit with active/passive checks, repeater, intercepting proxy, and HTML reports. | MIT |
| **[ProofCMS](https://github.com/pxawtyy/proofcms)** | [<img src="https://img.shields.io/github/stars/pxawtyy/proofcms?style=social&color=white" alt="proofcms stars"/>](https://github.com/pxawtyy/proofcms/stargazers) | Modular CMS vulnerability detector for WordPress and Joomla with evidence-based verification. | MIT |

---

## 🛠️ Additional Specialized Options

- **Arachni** — *[Legacy]* Modular web scanner; project is end-of-life (use OWASP ZAP or Wapiti).
- **OpenVAS** — Network and host-level vulnerability scanner (complements web DAST).
- **Lonkero** — High-performance Rust scanner focused on false-positive reduction.
- **Nmap** — Network mapper for host discovery and service version fingerprinting.
- **w3af** — Web application attack and audit framework.

---

## 🤝 How to Contribute

1. Fork this repository 🍴
2. Add your DAST tool or open-source scanner to `README.md` following the tabular format.
3. Ensure accurate pricing details, free tier limits, star counts, or company metrics are included.
4. Open a Pull Request (PR) with a brief summary of the changes.

---

## 💖 Support & Sponsorship

If you find this DAST resource list helpful in securing your application stack, please consider supporting the project!

- ⭐ **Star** this repository to help others discover it.
- 🔀 **Fork** and contribute new tools or updates.
- 📢 **Share** with your DevSecOps, AppSec, and Cybersecurity colleagues.
- ☕ **Buy me a coffee / Sponsor**: Support ongoing maintenance via [GitHub Sponsors](https://github.com/sponsors/ishandutta2007).

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Dynamic-Application-Security-Testing&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Dynamic-Application-Security-Testing&type=date&legend=top-left)

---

## ⚠️ Disclaimer

- This is a **community-curated** list for educational, security auditing, and research purposes.
- DAST tools must strictly be executed against web applications and infrastructure you own or have explicit authorization to test. Unauthorized penetration testing or scanning is illegal.
- Automated security scanners may produce false positives or false negatives; manual validation by AppSec professionals is recommended.

---

<p align="center">
  <b>Built for Security Engineers, DevSecOps Teams, Penetration Testers, and AppSec Professionals worldwide.</b>
</p>
