# Parakh Shinde
### Security Engineering | AI Security | Application Security | Python Security Tooling

I build and test security tools focused on AI application risks, Python static analysis, API security, and cloud authorization. My projects emphasize reproducible tests, reviewable findings, and clear documentation of what the evidence does—and does not—show.

**Focus:** AI/LLM security evaluation · Application security · Python security tooling · Secure APIs · Detection engineering

[Portfolio](https://parakh-shinde.github.io/) · [LinkedIn](https://www.linkedin.com/in/parakh-shinde) · [Resume](https://parakh-shinde.github.io/Parakh%20Shinde-resume.pdf)

---

## Selected Engineering Projects

### AST Auditor v0.4.0 — Python Static Analysis
An independently developed, rule-registry-driven Python SAST tool that parses source code without executing the scanned program and reports selected risky patterns.

- **Six rules:** dynamic `eval()`, dynamic `exec()`, selected pickle deserialization, selected shell-execution APIs, potentially unsafe `yaml.load()`, and literal `verify=False` in recognized module-level `requests` / `httpx` calls.
- **Output:** terminal text, JSON, and SARIF 2.1.0, with rule metadata, severity, confidence, CWE mapping, remediation, and source locations.
- **Validation:** 124 automated tests passed; Ruff checks passed; built wheel and source distribution; installed the published v0.4.0 wheel in a clean virtual environment.
- **Exploratory evaluation:** 46 supported cases matched labels, with zero labelled mismatches; two cases are explicitly unsupported and excluded from scoring. The small manually labelled corpus is not a measure of universal accuracy or production readiness.

**Release:** [v0.4.0 on GitHub](https://github.com/Parakh-Shinde/ast-auditor/releases/tag/v0.4.0) · [Source repository](https://github.com/Parakh-Shinde/ast-auditor)

### AegisForge — AI and API Security Lab
A controlled lab for exploring prompt-injection scenarios, guardrail behavior, authorization boundaries, telemetry, and benchmark-driven validation. The project documents both test outcomes and limitations.

**Technologies:** Python · API security · Prompt-injection testing · CI · CodeQL · Dependency scanning

[View repository](https://github.com/Parakh-Shinde/AegisForge)

### AegisAI — AI Security Evaluation Lab
A security-focused application exploring repeatable AI security workflows, authenticated APIs, runtime configuration validation, and controlled tool execution.

**Technologies:** Python · FastAPI · PostgreSQL · Redis · Docker · pytest

[View repository](https://github.com/Parakh-Shinde/aegisai)

### GCP-IAMGraph — Cloud Identity Analysis
A read-only Google Cloud IAM analysis project that models inherited policies and authorization outcomes, with documented privilege-escalation rules and attack-graph output.

[View repository](https://github.com/Parakh-Shinde/GCP-IAMGraph)

---

## Technical Interests

- **AI Security:** LLM application risks, prompt injection, jailbreak evaluation, tool-injection scenarios, responsible red-team testing
- **Application Security:** Secure coding, Python static analysis, API authorization, vulnerability triage, SARIF
- **Cloud & Detection:** Google Cloud IAM, AWS audit telemetry, Splunk SPL, MITRE ATT&CK, investigation workflows
- **Engineering:** Python, FastAPI, pytest, Ruff, GitHub Actions, Docker, Linux/WSL, REST APIs

Skills reflect hands-on projects and ongoing learning; proficiency varies by technology.

## Education

**Master of Computer Applications (MCA)** — Vellore Institute of Technology (VIT)  
**Bachelor of Computer Applications (BCA)** — Rabindranath Tagore University (RNTU), 2025

## Engineering Principles

- Validate behavior with repeatable tests and documented evaluation methods.
- Treat security findings as signals for human review, not automatic proof of exploitability.
- Document unsupported cases, false-positive risks, and scope boundaries.
- Practice security testing in authorized labs and controlled environments.

## Connect

I’m interested in entry-level and internship opportunities involving AI security, application security, and security engineering.

[LinkedIn](https://www.linkedin.com/in/parakh-shinde) · [Portfolio](https://parakh-shinde.github.io/) · [GitHub repositories](https://github.com/Parakh-Shinde?tab=repositories)
