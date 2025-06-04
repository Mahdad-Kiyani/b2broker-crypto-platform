# B2Broker Crypto Platform

This repository documents the backend architecture and infrastructure engineering work delivered for B2Broker’s institutional-grade crypto exchange platform. It covers the implementation of a modular API layer, secure wallet infrastructure, KYC pipelines, and ultra-low-latency matching engine integrations.

## ⚙️ Tech Stack

- FastAPI, WebSocket, GraphQL
- PostgreSQL (WAL), Redis, Kafka, ZeroMQ
- Docker, Kubernetes, Helm, GitLab CI/CD, FluxCD
- IdentityMind, PGP, Tesseract OCR
- Prometheus, Grafana, Alertmanager

## 🔐 Key Contributions

- Built REST + WebSocket APIs with HMAC-SHA256 signing
- Integrated ZeroMQ middleware to connect frontend to C++ matching engine
- Designed PostgreSQL WAL-based ledger & recovery logic
- Engineered secure hot-to-cold wallet transitions with air-gapped approval
- Implemented admin RBAC API with audit trails and mTLS

## 📊 Compliance & Monitoring

- Identity verification via IdentityMind API and fallback queue
- CRON-based fraud report generation
- Real-time monitoring of wallet health, order latency, and transfer queues

## 🚀 Outcome

- 35% API latency reduction with Redis optimization
- >99.99% service uptime
- Automated onboarding for 100+ ERC-20 tokens
- >93% KYC verification success on first attempt

---

## 🧪 Getting Started (Placeholder)

Future updates will include API schemas, CI/CD templates, and anonymized infra blueprints for high-throughput trading environments.

