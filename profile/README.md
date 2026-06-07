# COMP47250 - Anti-Cheat Exam Portal

**AEGIS (Adaptive Exam Guardian and Integrity System)** is a browser-native online exam platform that detects suspicious AI-assisted behaviour using real-time telemetry, without webcams, browser extensions, or invasive proctoring.

Built by School of Computer Science students at University College Dublin as part of COMP47250 Team Software Project

## How it works

1. Students take exams in an isolated React exam shell after acknowledging a GDPR transparency notice.
2. A lightweight Telemetry SDK captures tab switches, paste events, keystroke intervals, and answer timing - no key content, clipboard text, or screen recordings.
3. A signal scorer combines six behavioural signals into a 0-1 confidence score.
4. Professors review an integrity report showing the scrore and flagged event timeline. The system produces **evidence for human review, not automatic verdicts**.

## Repositories
| Repo | Description |      
| ----- | ----------- |
| [AEGIS](https://github.com/comp47250-team-project/AEGIS) | Main monorepo - backend, frontend, infra, CI / CD |       


## Stack

FastAPI, React, TypeScript, PostgreSQL, Azure Container Apps, Azure Service Bus, Docker Compose, GitHub Actions

