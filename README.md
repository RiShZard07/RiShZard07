# Rishi Damarla

Statistics & Machine Learning at Carnegie Mellon (B.S., December 2027). Last summer I built a production Python package for retention experiment evaluation at Comcast. I like work where correctness is testable: decision systems you can evaluate offline, backends with durable state and idempotent APIs, and evaluation harnesses for LLM features.

## Projects

| Project | Stack | What it is |
|---|---|---|
| [nba-decision-engine](https://github.com/RiShZard07/nba-decision-engine) | Python, scikit-learn, pandas, NumPy | Next-best-action decision engine on a synthetic subscription base: uplift models (T-, S-, X-learners), contextual bandits (LinUCB, Thompson sampling), offline policy evaluation (IPS, SNIPS, DM, DR with bootstrap intervals), eligibility, budget and contact-cap guardrails, plain-language explanations, 63 tests and a CI gate checked against simulator truth |
| [dispatch-service](https://github.com/RiShZard07/dispatch-service) | Python, FastAPI, SQLAlchemy, SQLite, Docker | Order-dispatch API for a synthetic delivery marketplace: idempotent order creation, SQL-backed state machine, transactional nearest-courier assignment that holds under concurrent requests, optimistic versioning with If-Match, server-sent event feed, transactional outbox with webhook retries, Prometheus-style metrics, S3 export (boto3, tested with moto), 125 tests, Docker image and Render blueprint |
| [courier-app](https://github.com/RiShZard07/courier-app) | TypeScript, React Native, Expo, Jest | Courier-side mobile client for dispatch-service: typed API client with request ids, timeouts and the backend's error envelope, If-Match transitions with 409 handling, expo-router screens, 80 Jest tests, web build with Vercel config |
| [ticket-triage-agent](https://github.com/RiShZard07/ticket-triage-agent) | Python, Claude API (tool use) | LLM agent that triages tickets through typed tools, with guardrails, PII redaction, a 40-ticket evaluation harness, a CI regression gate, and JSON-lines telemetry |
| [station-analytics](https://github.com/RiShZard07/station-analytics) | Python, pandas, NumPy, SQLite | Measurement-system analytics for messy multi-station test data: schema-drift handling, station-name canonicalization, Gauge R&R, Cpk, control charts, EWMA/CUSUM drift and change-point detection, calibration alerts, 61 tests and a CI gate that proves every injected fault is caught |
| [casedesk](https://github.com/RiShZard07/casedesk) | Java 17, React, Playwright, GitHub Actions | Support-ticket service: priority-queue routing, idempotency keys, write-ahead journal with restart recovery, 24 test groups + 6 browser scenarios in CI |
| [pokemon-commerce-bi](https://github.com/RiShZard07/pokemon-commerce-bi) | Python, SQL, SQLite | ETL pipeline and dimensional warehouse with validation, quarantine, transactional refresh, and 14 tests |

All seven are AI-assisted builds (Claude Code, ChatGPT/Codex) that I reviewed, tested, and extended; each README says exactly what is and is not claimed, and each repo has a VERIFIED_RESULTS.md with the commands and numbers behind every claim.

## Elsewhere

- [LinkedIn](https://www.linkedin.com/in/rishikeshava-damarla-b0524a227/)
- rdamarla@andrew.cmu.edu
