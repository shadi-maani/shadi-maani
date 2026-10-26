# Shadi Maani

Security researcher based in Syria, focused on web application and AI security. I've been doing hands-on offensive work since 2020 — finding the bugs, writing them up so they actually get fixed, and handling things when an incident happens.

I also build what I test. Security came first for me, then I spent a stretch as a developer, designing and shipping **Thimma**, an AI-powered debt ledger with a Python backend on GCP and a Flutter app, before coming back to security. So I read code, pipelines and cloud configs from the builder's side too.

---

## What I work with

**Offensive Security**
Web application pentesting · Bug bounty methodology · OSINT · Burp Suite · Caido · OWASP ZAP · nmap · Shodan · Censys

**AI & LLM Security**
Prompt injection · Agent sandbox escapes · LLM pipeline hardening

**Defense & Incident Response**
Vulnerability disclosure programs (HackerOne) · Incident response · SPF / DKIM / DMARC · Exposed-asset discovery · Access control review

**Secure Development & Cloud**
Python · Flask · REST APIs · Docker · GitHub Actions · Google Cloud Run · IAM · API Gateway · Vertex AI · Workload Identity Federation · Gitleaks · Bandit · Safety · Trivy

**Mobile**
Flutter · Dart · Firebase Auth · Cloud Firestore

**Systems & Tooling**
Linux (Fedora, Ubuntu — daily driver, ~2 years) · Bash · Git · Docker Compose · Networking fundamentals · gcloud CLI

---

## Security work

**SYNC NGO — Security volunteer** *(May 2026 – present)*
Ran a multi-cycle security assessment of the organization's AI recruitment platform during development and documented 19 findings (3 High, 10 Medium, 6 Low), each written up with reproduction steps and tracked through remediation. Set up the organization's first vulnerability disclosure program on HackerOne, including its scope, safe-harbor terms and triage workflow. Led the response to a malware and credential-theft incident and wrote the incident-response runbook.

**Perplexity AI — Sandbox network-isolation bypass**
Reported unauthorized outbound network access from an environment that was meant to be isolated. Accepted and resolved.

---

## Projects

**[Thimma — Backend](https://github.com/shadi-maani/thimma-backend-showcase)**
AI pipeline that converts unstructured Arabic voice or text into structured financial records. Handles up to 5 simultaneous debt operations per request. Built with Vertex AI function calling (`Mode.ANY`), Speech-to-Text V2 Chirp 3, a hardcoded linguistic logic matrix for zero-hallucination direction detection, and a 45-case golden test dataset. On the security side: Cloud Run is closed to unauthenticated traffic behind API Gateway, CI/CD is keyless through Workload Identity Federation, Vertex AI quota is zeroed across all regions with an Org Policy model allowlist, and Gitleaks, Bandit, Safety and Trivy run in the pipeline on every push.

**Thimma — Flutter App** *(private)*
Cross-platform mobile app for the same system. Covers Firebase Auth (email, Google, verification gate), Firestore smart sync with FIFO settlement logic, voice recording flow, Arabic PDF statement export, scheduled notifications, and 140+ unit/widget/integration tests.

**KDE Plasma Widget**
A desktop widget for KDE Plasma. JavaScript/QML.

**Network Automation**
Scripts for CCNA-level lab environments and network configuration tasks.

---

## Background

Self-taught. I started with CompTIA fundamentals (A+, Network+, Security+) and CCNA-level networking as self-study, then moved into Linux system administration and automation scripting. I've been practicing offensive security on PortSwigger Web Security Academy and Hack The Box since 2020, and I've worked through the OSCP, CEH and Linux+ curricula on my own, without taking the exams yet.

About two years ago I switched to Linux as my primary OS, and that's when I started building real applications. Shipping Thimma end to end taught me how backends, CI/CD and cloud IAM get put together in practice, which is a big part of what I look at now when I test someone else's.

Currently working through the **IBM DevOps & Software Engineering Professional Certificate** (in progress). I'm also in my first year of a B.A. in English Literature at Damascus University (B2 English), which helps me write clear reports and technical documentation.

---

## Contact

Open to security roles — application security, penetration testing and AI security — remote or on-site in Syria. Backend work too. Best reached via GitHub issues or email.

[shadimaani.me](https://shadimaani.me) · [contact@shadimaani.me](mailto:contact@shadimaani.me)
