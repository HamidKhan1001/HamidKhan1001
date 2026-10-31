# Hamid Naeem Khan

Software engineer and 🚩 **GitHub Campus Expert**, based in Peshawar, Pakistan. I work on backend systems in Go and Python, mostly around Kubernetes operators and database tooling, and I do most of my learning by contributing to open source.

B.Sc. Software Engineering at UET Peshawar. Co-organizer of CNCF Community Peshawar.

<p>
  <a href="https://www.linkedin.com/in/hamid-naeem-khan-278413402/"><img src="https://img.shields.io/badge/LinkedIn-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://leetcode.com/u/hamidkhan1001/"><img src="https://img.shields.io/badge/LeetCode-1c1c1c?style=flat-square&logo=leetcode&logoColor=ffa116" alt="LeetCode" /></a>
  <img src="https://komarev.com/ghpvc/?username=HamidKhan1001&label=Profile%20views&color=8957e5&style=flat-square" alt="Profile views" />
</p>

## Open source

I like reading a codebase until I understand why it is the way it is, then fixing what is actually broken. I try to write tests that fail before the fix.

**[OpenEverest](https://github.com/openeverest/openeverest)** (Go, Kubernetes): database provisioning on Kubernetes. Three merged PRs, all about errors that were swallowed or unhelpful.
- [#3118](https://github.com/openeverest/openeverest/pull/3118): report the actual assignee and likely cause when a delegated assign fails, instead of a generic error.
- [#2943](https://github.com/openeverest/openeverest/pull/2943): return previously dropped errors from the monitoring instance handler so failures reach controller-runtime.
- [#2945](https://github.com/openeverest/openeverest/pull/2945): the same fix for the monitoring config secret update, backported to v2.

**[AOSSIE](https://github.com/AOSSIE-Org)**: EduAid, a setup audit and a fix for an invalid PyTorch version pin that broke fresh installs. Resonate, a diagnosis of a memory leak in GSAP timeline cleanup.

**[Tales of OpenEverest](https://github.com/HamidKhan1001/TalesOfOpenEverest)**: a write-up of the contribution process as it happened, including review comments and mistakes.

## 🚩 Community

As a Campus Expert I help students at UET Peshawar get started with Git, GitHub and open source: workshops, events and first pull requests. With CNCF Community Peshawar I help organize local talks and meetups.

## Selected projects

| Project | What it is |
|---|---|
| [system-design-distributed-cache](https://github.com/HamidKhan1001/system-design-distributed-cache) | LRU and LFU caches with O(1) operations, a stampede shield, and a sharded wrapper. The README documents the tradeoffs and where it is not a real distributed system. |
| [url_shortner](https://github.com/HamidKhan1001/url_shortner) | URL shortener in Go: Gin, PostgreSQL, Redis read-through cache, Docker Compose, CI, graceful shutdown. |
| [system-design-rate-limiter-cluster](https://github.com/HamidKhan1001/system-design-rate-limiter-cluster) | Redis token-bucket rate limiter, one atomic Lua script per decision, with a concurrency test. |
| [api-idempotency-key-manager](https://github.com/HamidKhan1001/api-idempotency-key-manager) | FastAPI middleware for safe retries using an atomic Redis `SET NX` claim. Known limitations are listed. |
| [system-design-distributed-id-generator](https://github.com/HamidKhan1001/system-design-distributed-id-generator) | Snowflake-style 64-bit IDs. Raises on clock regression. |

More in the [system-design series](https://github.com/HamidKhan1001?tab=repositories&q=system-design).

## Stack

<p>
  <img src="https://skillicons.dev/icons?i=go,py,ts,c,cpp,kubernetes,docker,linux,postgres,redis,kafka,fastapi,nodejs,prometheus,grafana&perline=8" alt="Go, Python, TypeScript, C, C++, Kubernetes, Docker, Linux, PostgreSQL, Redis, Kafka, FastAPI, Node.js, Prometheus, Grafana" />
</p>

I like boring, predictable software, especially the kind that fails loudly instead of quietly.
