# Shadi Maani

Backend and mobile developer based in Syria. I build things end to end — from Python APIs running on GCP to Flutter apps shipping on Android, iOS, and macOS.

Most of my current work lives inside **Thimma**, an AI-powered debt ledger I designed and built for informal Arabic-speaking economies, where people track debts verbally and never in writing. The backend parses colloquial Syrian Arabic voice input into structured financial operations using Vertex AI with forced function calling. The mobile app handles the rest.

---

## What I work with

**Backend & Cloud**
Python · Flask · Google Cloud Run · Vertex AI (Gemini) · Google Speech-to-Text V2 · API Gateway · Docker · GitHub Actions · Workload Identity Federation · pytest

**Mobile**
Flutter · Dart · Firebase Auth · Cloud Firestore · REST APIs · State management (ChangeNotifier / ValueNotifier) · Push notifications · PDF generation · Audio recording

**Systems & Tooling**
Linux (daily driver, ~2 years) · Bash · Git · Docker Compose · Gitleaks · Bandit · Trivy · Safety · gcloud CLI

---

## Projects

**[Thimma — Backend](https://github.com/shadi-maani/thimma-backend-showcase)**
AI pipeline that converts unstructured Arabic voice or text into structured financial records. Handles up to 5 simultaneous debt operations per request. Built with Vertex AI function calling (`Mode.ANY`), Speech-to-Text V2 Chirp 3, a hardcoded linguistic logic matrix for zero-hallucination direction detection, and a 45-case golden test dataset. Deployed on Cloud Run behind an API Gateway with keyless CI/CD via Workload Identity Federation.

**Thimma — Flutter App** *(private)*
Cross-platform mobile app for the same system. Covers Firebase Auth (email, Google, verification gate), Firestore smart sync with FIFO settlement logic, voice recording flow, Arabic PDF statement export, scheduled notifications, animated UI with glassmorphism, and 140+ unit/widget/integration tests.

**KDE Plasma Widget**
A desktop widget for KDE Plasma. JavaScript/QML.

**Network Automation**
Scripts for CCNA-level lab environments and network configuration tasks.

---

## Background


Self-taught backend and mobile developer based in Syria. My journey started with CompTIA fundamentals (A+, Network+, Security+) and CCNA-level networking, then moved into Linux system administration and automation scripting. About two years ago, I switched to Linux as my primary OS — and that’s when I started building real applications.

I independently designed and shipped **Thimma**, a full-stack AI-powered debt management platform, owning the entire lifecycle: from Python backend on GCP (Cloud Run, Vertex AI, Speech-to-Text) to a cross-platform Flutter app (Firebase, REST, state management, PDF generation, and 140+ tests). Along the way, I implemented production-grade CI/CD with GitHub Actions, Docker multi-stage builds, keyless GCP auth via Workload Identity Federation, and security scanning (Gitleaks, Bandit, Trivy).

Currently working through the **IBM DevOps & Software Engineering Professional Certificate** (in progress), applying Docker, microservices, and automated testing directly to active projects. I also hold a first‑year B.A. in English Literature from Damascus University (B2 English), which helps me write clear technical documentation and communicate effectively in professional settings.

English B2 — comfortable reading API specs, writing documentation.
---

## Contact

Open to backend or Flutter roles, remote. Best reached via GitHub issues or email.
[shadimaani.me](https://shadimaani.me) | [contact@shadimaani.me](mailto:contact@shadimaani.me)
