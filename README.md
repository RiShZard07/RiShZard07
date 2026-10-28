# Rishi Damarla

Statistics & Machine Learning at Carnegie Mellon (B.S., December 2027). Last summer I built a production Python package for retention experiment evaluation at Comcast. I like backend work where correctness is testable: queues, idempotency, durable state, and evaluation harnesses for LLM features.

## Projects

| Project | Stack | What it is |
|---|---|---|
| [station-analytics](https://github.com/RiShZard07/station-analytics) | Python, pandas, NumPy, SQLite | Measurement-system analytics for messy multi-station test data: schema-drift handling, station-name canonicalization, Gauge R&R, Cpk, control charts, EWMA/CUSUM drift and change-point detection, calibration alerts, 61 tests and a CI gate that proves every injected fault is caught |
| [casedesk](https://github.com/RiShZard07/casedesk) | Java 17, React, Playwright, GitHub Actions | Support-ticket service: priority-queue routing, idempotency keys, write-ahead journal with restart recovery, 24 test groups + 6 browser scenarios in CI |
| [ticket-triage-agent](https://github.com/RiShZard07/ticket-triage-agent) | Python, Claude API (tool use) | LLM agent that triages tickets through typed tools, with guardrails, PII redaction, a 40-ticket evaluation harness, a CI regression gate, and JSON-lines telemetry |
| [pokemon-commerce-bi](https://github.com/RiShZard07/pokemon-commerce-bi) | Python, SQL, SQLite | ETL pipeline and dimensional warehouse with validation, quarantine, transactional refresh, and 14 tests |

All four are AI-assisted builds (ChatGPT/Codex and Claude Code) that I reviewed, tested, and extended; each README says exactly what is and is not claimed.

## Elsewhere

- [LinkedIn](https://www.linkedin.com/in/rishikeshava-damarla-b0524a227/)
- rdamarla@andrew.cmu.edu
