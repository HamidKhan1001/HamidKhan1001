# Hamid Naeem Khan

Software engineer. B.Sc. Software Engineering student at UET Peshawar. I build backend software in Go and Python and am currently going deeper on Kubernetes (operators and controllers) and applied AI systems.

Based in Pakistan. Co-organizer of CNCF Community Peshawar.

[Portfolio](https://portfolio-hamid-khan.vercel.app) | [LinkedIn](https://linkedin.com/in/hamid-khan-96548833b) | [LeetCode](https://leetcode.com/u/hamidkhan1001/) | hamidkhanpubgid@gmail.com

## Open source

### OpenEverest (Go, TypeScript, Kubernetes)

[OpenEverest](https://github.com/openeverest/openeverest) is an open-source platform for provisioning and managing databases on Kubernetes.

Merged:
- [#3118](https://github.com/openeverest/openeverest/pull/3118): include the actual assignee and likely cause in the error returned when a delegated assign fails.
- [#2943](https://github.com/openeverest/openeverest/pull/2943): return previously dropped errors from the monitoring instance handler so reconcile failures surface to controller-runtime.
- [#2945](https://github.com/openeverest/openeverest/pull/2945): same fix for the monitoring config secret update, backported to v2.

In review:
- [#2995](https://github.com/openeverest/openeverest/pull/2995): allow configuring resource limits on restore job containers.
- [#3203](https://github.com/openeverest/openeverest/pull/3203): fix the v2 quick start so Tilt is configured before it is started.
- [provider-percona-server-mongodb](https://github.com/openeverest/provider-percona-server-mongodb): map Backup and Restore timestamps from the operator's real status.
- [plugin-audit](https://github.com/openeverest/plugin-audit): migrate the audit consumer off the removed session endpoint.

### Other

- [AOSSIE-Org/EduAid](https://github.com/AOSSIE-Org/EduAid): open PRs fixing an invalid PyTorch version pin and handling a missing Sense2Vec model and invalid Google credentials at startup.
- [drasi-project/learning](https://github.com/drasi-project/learning): open PRs on documentation and demo scripts.

## Projects

| Project | Description |
|---|---|
| [url_shortner](https://github.com/HamidKhan1001/url_shortner) | URL shortener in Go with base62 key generation, a redirect handler, and unit tests. |
| [system-design-*](https://github.com/HamidKhan1001?tab=repositories&q=system-design) | Small Python implementations of distributed-systems building blocks, each with tests: LRU/LFU cache with stampede protection, Redis token-bucket rate limiter, chunked blob storage with replication, web crawler frontier, notification router with retries and dead-letter queue, Snowflake-style ID generator. |
| [fastapi-api-key-rotation](https://github.com/HamidKhan1001/fastapi-api-key-rotation), [api-idempotency-key-manager](https://github.com/HamidKhan1001/api-idempotency-key-manager), [sqlalchemy-async-soft-delete](https://github.com/HamidKhan1001/sqlalchemy-async-soft-delete) | Reusable FastAPI and SQLAlchemy components for API key lifecycle, idempotent retries, and soft deletes. |
| [Cortexium](https://github.com/HamidKhan1001/cortexium) | Early-stage work on AI runtime sandboxing and backend orchestration. |

## Languages and tools

- Languages: Go, Python, TypeScript, C, C++, SQL
- Infrastructure: Kubernetes (operators, controller-runtime), Docker, Nginx, Linux, AWS
- Data: PostgreSQL, Redis, Kafka
- Backend: FastAPI, Node.js
- Observability: Prometheus, Grafana
