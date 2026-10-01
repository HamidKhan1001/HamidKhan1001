# Hamid Naeem Khan

Software engineer. I build backend systems in Go and Python, and I spend most of my open-source time inside Kubernetes operators and database tooling. I am currently going deeper on controller design and applied AI systems.

B.Sc. Software Engineering, UET Peshawar. Co-organizer of CNCF Community Peshawar. Based in Pakistan.

[LinkedIn](https://linkedin.com/in/hamid-khan-96548833b)

I read error handling the way some people read mystery novels, mostly to find where the bodies are buried. That habit is where most of my open-source fixes come from.

## Stack

<p>
  <img src="https://skillicons.dev/icons?i=go,py,ts,c,cpp&perline=10" alt="Go, Python, TypeScript, C, C++" />
</p>
<p>
  <img src="https://skillicons.dev/icons?i=kubernetes,docker,linux,nginx,aws&perline=10" alt="Kubernetes, Docker, Linux, Nginx, AWS" />
</p>
<p>
  <img src="https://skillicons.dev/icons?i=postgres,redis,kafka,fastapi,nodejs&perline=10" alt="PostgreSQL, Redis, Kafka, FastAPI, Node.js" />
</p>
<p>
  <img src="https://skillicons.dev/icons?i=prometheus,grafana&perline=10" alt="Prometheus, Grafana" />
</p>

## Featured project

**[system-design-distributed-cache](https://github.com/HamidKhan1001/system-design-distributed-cache)** (Python)

LRU and LFU caches with O(1) operations, a stampede shield that collapses concurrent recomputation of a hot key into a single call, and a sharded wrapper. The README documents the design, the tradeoffs, and the known limits, including where it is not a real distributed system. 36 tests.

## Open source contributions

### OpenEverest (Go, Kubernetes)

[OpenEverest](https://github.com/openeverest/openeverest) provisions and manages databases on Kubernetes. Merged pull requests:

- [#3118](https://github.com/openeverest/openeverest/pull/3118): report the actual assignee and likely cause when a delegated assign fails, instead of a generic error.
- [#2943](https://github.com/openeverest/openeverest/pull/2943): return previously dropped errors from the monitoring instance handler, so failures reach controller-runtime instead of disappearing.
- [#2945](https://github.com/openeverest/openeverest/pull/2945): the same fix for the monitoring config secret update, backported to v2.

## More projects

| Project | Description |
|---|---|
| [url_shortner](https://github.com/HamidKhan1001/url_shortner) | URL shortening service in Go. Gin API, PostgreSQL storage, Redis read-through cache, Docker Compose, CI. Layered architecture with collision retry and graceful shutdown. |
| [system-design-rate-limiter-cluster](https://github.com/HamidKhan1001/system-design-rate-limiter-cluster) | Redis token-bucket rate limiter where each decision is one atomic Lua script. Tested with a concurrency test. |
| [api-idempotency-key-manager](https://github.com/HamidKhan1001/api-idempotency-key-manager) | FastAPI middleware for safe request retries using an atomic Redis `SET NX` claim. README lists its known limitations. |
| [system-design-distributed-id-generator](https://github.com/HamidKhan1001/system-design-distributed-id-generator) | Snowflake-style 64-bit IDs: 41-bit timestamp, datacenter and worker bits, 12-bit sequence. Raises on clock regression. |
| [system-design-*](https://github.com/HamidKhan1001?tab=repositories&q=system-design) | The rest of the series: blob storage, web crawler frontier, notification router, chat hub, analytics ingestion. Small, tested Python implementations. |
