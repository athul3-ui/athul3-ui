# Hey, I'm Athul 👋

I'm an **Application Security & DevSecOps Engineer** based in Kochi, Kerala with 7+ years of engineering experience — 3+ years dedicated to AppSec and DevSecOps at Acabes International, the fintech arm of Arab Bank, and 4 years prior at NPOL–DRDO in a classified defence engineering environment.

My work sits at the intersection of security and software delivery. I build automated security gates, embed SAST/DAST/SCA into CI/CD pipelines, and work directly with development teams to make secure coding feel like a natural part of how they ship — not a blocker at the end.

---

## What I work with

**Security Testing**
`Fortify` `WebInspect` `Burp Suite` `OWASP ZAP` `BlackDuck` `Snyk` `Trivy` `SonarQube` `Audit Workbench`

**DevSecOps & CI/CD**
`GitHub Actions` `Jenkins` `GitLab CI/CD` `Docker` `Ansible` `HashiCorp Vault`

**AppSec Practices**
`SAST` `DAST` `SCA` `Threat Modelling` `Penetration Testing` `Secure Code Review` `IaC Security`

**Frameworks & Standards**
`OWASP Top 10` `MITRE ATT&CK` `STRIDE` `PASTA` `NIST CSF` `ISO 27001` `PCI DSS`

**Scripting**
`Python` `Bash` `PowerShell`

---

## Projects

### 🔍 [jenkins-fortify-scan-reporter](https://github.com/athul3-ui/jenkins-fortify-scan-reporter)
Pulls Fortify SAST stage durations from Jenkins pipelines via REST API and exports a formatted Excel report — multi-sheet breakdown, colour-coded rows, and a doughnut chart showing scan duration distribution. Built to replace manual job-by-job checking across 50+ pipelines. Works for any Jenkins stage, not just Fortify.

### 🛡️ [fortify-sast-pipeline-gate](https://github.com/athul3-ui/fortify-sast-pipeline-gate)
A Jenkins pipeline stage that runs a full Fortify SAST scan (clean → translate → scan → upload to SSC) and breaks the pipeline if Critical or High severity findings are detected. No clean scan, no deploy. Drop it into any existing Jenkinsfile.

### 🔒 [fortify-sast-gitlab-ci](https://github.com/athul3-ui/fortify-sast-gitlab-ci)
A GitLab CI template that runs Fortify SAST and handles SSC app/version creation automatically — no manual SSC setup needed. Mirrors your Git branch structure in SSC (one app per repo, one version per branch). Includes a GitHub Actions equivalent for teams not on GitLab.

---

## A bit of background

At Acabes International I led the Shift-Left security initiative across multiple application teams — integrating automated security gates into GitHub Actions and Jenkins pipelines, running threat modelling sessions using STRIDE and MITRE ATT&CK, conducting manual penetration testing and secure code reviews, and managing secrets across 100+ microservices via HashiCorp Vault. I also validated iOS and Android mobile application shielding controls before each production release.

Before AppSec, I spent four years at NPOL–DRDO as a Project Engineer on a mission-critical signal visualisation system for underwater defence applications. That environment — classified, high-stakes, zero tolerance for undocumented changes — built habits around rigorous documentation and security-first thinking that I carry into everything I do now.

I hold the **Certified DevSecOps Professional (CDP)** certification from Practical DevSecOps and am currently pursuing the **AWS Certified Security Specialist**.

---

## Certifications

- 🎓 Certified DevSecOps Professional (CDP) — Practical DevSecOps
- 🔄 AWS Certified Security Specialist — In Progress

---

## Get in touch

- 💼 [LinkedIn](https://linkedin.com/in/athulshibu)
- 📧 iamathulhere3@gmail.com
- 📍 Kochi, Kerala

---

*Open to Senior Application Security and DevSecOps Engineer roles — preferably in Kerala or remote-friendly.*
