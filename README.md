# Shadi Maani

I'm a security researcher in Syria. I mostly work on web application and AI security, and I've been doing offensive work since 2020.

Security came first for me. Then I spent a while as a developer and built **Thimma**, an AI debt ledger with a Python backend on GCP and a Flutter app, and after that I came back to security. That detour means I can read the code and cloud setup of what I'm testing.

---

## How I work

The useful thing to know about me isn't my toolset, it's how I approach a target.

I form theories and test them. While I'm gathering information and while I'm hunting, I keep a running set of guesses about how the thing works and where it might break, and I go after them one by one. I retry things two or three times even when I'm repeating what looks like the same request, because the second or third attempt is often where something nobody noticed turns up. For recon I lean on the known frameworks and handbooks rather than improvising.

My workflow is an intercepting proxy like anyone else's, but I run more of it through AI than most people do: I use it to move faster, to check a theory, and to generate and fire request variations quickly instead of by hand.

With AI and LLM targets I start by finding the edges: what the model can do, what tools it has, what rules it's been given, and then I try to break out of them. On the building side I harden LLM pipelines so a bad model output can't turn into a bad record.

On defense I work incidents against NIST and the standard frameworks rather than ad hoc. I read email headers and check SPF, DKIM and DMARC. For access control I go past "can this user reach this" into the code and the auth path, and into the development decisions behind them. I've also spent time on the detection side with Suricata and SIEM, reading logs and writing rules for the kinds of activity I know from the attacking side.

---

## Tooling

Where the tool itself matters:

**Detection and monitoring:** Suricata · SIEM · log analysis
**Web and recon:** Burp Suite · Caido · OWASP ZAP · nmap · Shodan · Censys
**Secure development and cloud:** Python · Google Cloud (Cloud Run, Vertex AI, API Gateway, IAM) · Docker · GitHub Actions · Workload Identity Federation · Gitleaks · Bandit · Safety · Trivy
**Mobile:** Flutter · Dart · Firebase Auth · Cloud Firestore
**Systems:** Linux (Fedora and Ubuntu, daily driver for about 2 years) · Bash · Git · networking fundamentals

---

## Security work

**SYNC NGO, security volunteer** *(May 2026 to present)*
I tested the organization's AI recruitment platform over several rounds while it was being built. I wrote up 19 findings (3 High, 10 Medium, 6 Low) with reproduction steps and followed each one until it was fixed. I also set up the organization's first vulnerability disclosure program on HackerOne, with its scope, safe-harbor terms and triage process. I led the response to a malware and credential-theft incident and then wrote the incident-response runbook.

**Perplexity AI, sandbox network-isolation bypass**
A sandbox that was supposed to be isolated could still make outbound network connections. I reported it, and Perplexity accepted and fixed it.

---

## Projects

**[Thimma backend](https://github.com/shadi-maani/thimma-backend-showcase)**
Takes Arabic voice or text and turns it into structured debt records, up to 5 operations per request. It uses Vertex AI function calling (`Mode.ANY`), Speech-to-Text V2 Chirp 3, a hardcoded linguistic logic matrix for direction detection, and a 45-case golden test set. Cloud Run is closed to unauthenticated traffic and sits behind API Gateway key auth. CI/CD has no stored keys and authenticates through Workload Identity Federation. Vertex AI quota is set to zero across all regions, with an Org Policy model allowlist on top, and Gitleaks, Bandit, Safety and Trivy run on every push.

**Thimma Flutter app** *(private)*
The mobile app for the same system: Firebase Auth with email, Google and a verification gate, Firestore sync with FIFO settlement, voice recording, Arabic PDF statements, scheduled notifications, and over 140 unit, widget and integration tests.

**KDE Plasma widget**
A desktop widget for KDE Plasma, written in JavaScript and QML.

**Network automation**
Scripts for CCNA-level labs and network configuration.

---

## Background

I'm self-taught. I started by studying CompTIA A+, Network+ and Security+ material and CCNA-level networking on my own, then moved on to Linux administration and scripting. I've practiced on PortSwigger Web Security Academy and Hack The Box since 2020. I've also gone through the OSCP, CEH and Linux+ material, but I haven't taken those exams yet.

I switched to Linux as my main OS about two years ago, and that's when I started building real applications. Building Thimma from start to finish showed me how backends, CI/CD and cloud IAM are put together, and I look at those same things when I test other people's systems.

I'm in my second year of a B.A. in English Literature at Damascus University. My English is at B2 level.

---

## Contact

I'm looking for security work (application security, penetration testing or AI security), remote or on-site in Syria. I'm open to backend roles as well. You can reach me through GitHub issues or by email.

[shadimaani.me](https://shadimaani.me) · [contact@shadimaani.me](mailto:contact@shadimaani.me)
