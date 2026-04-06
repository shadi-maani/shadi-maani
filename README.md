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

Self-taught, working from Syria. I started with CompTIA and networking fundamentals, moved into Linux and system administration, and eventually into backend development and mobile. I switched to Linux as my primary OS about two years ago and haven't looked back.

Currently working through the IBM DevOps & Software Engineering Professional Certificate while applying the concepts directly in production.

English B2 — comfortable reading documentation, writing technical content, and communicating in professional contexts.

---

## Contact

Open to backend or Flutter roles, remote. Best reached via GitHub issues or email.
[shadimaani.me](https://shadimaani.me) | [contact@shadimaani.me](mailto:contact@shadimaani.me)
