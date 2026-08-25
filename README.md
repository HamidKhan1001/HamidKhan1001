<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=Hamid%20Naeem%20Khan&fontSize=44&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Systems%20Engineer%20%E2%80%A2%20Cloud-Native%20%E2%80%A2%20Operator%20Architecture&descAlignY=56&descSize=17"/>

[![Portfolio](https://img.shields.io/badge/Portfolio-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white)](https://portfolio-hamid-khan.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/hamid-khan-96548833b)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/hamidkhan1001/)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hamidkhanpubgid@gmail.com)
[![CNCF Peshawar](https://img.shields.io/badge/CNCF_Peshawar-Co--Organizer-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)](https://community.cncf.io)
[![Profile Views](https://komarev.com/ghpvc/?username=HamidKhan1001&color=6e40c9&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/HamidKhan1001)

<br/>

⏱️ **2,000+ hours** across Go, Python & Kubernetes operators &nbsp;·&nbsp; building since 2023

</div>

---

My Kubernetes cluster has better uptime than my sleep schedule.

Software engineering student at UET Peshawar. Founder of Cortexium, building AI runtime sandboxes and backend orchestration infrastructure. Co-organizer of CNCF Peshawar. I contribute Go patches to production Kubernetes operators and implement distributed systems at the storage and protocol layer.

- Founder of **Cortexium** (AI runtime isolation and backend orchestration)
- Co-organizer, **CNCF Community Peshawar**
- Contributor to `openeverest/openeverest` (Go Kubernetes database operator)
- B.Sc. Software Engineering, **UET Peshawar**

---

## 🛠️ Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### Cloud & Infrastructure
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### Observability
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

### Backend & AI Runtimes
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![ONNX Runtime](https://img.shields.io/badge/ONNX_Runtime-005CED?style=for-the-badge&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=google&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

---

## 🌐 Open Source Contributions

### [openeverest/openeverest](https://github.com/openeverest/openeverest) · Kubernetes Operator / Database Lifecycle

| Commit | Description | Root cause |
|---|---|---|
| `fix(rbac)` | Check informer init and wrap watcher error | RBAC informer panicked on cold-start due to nil dereference. Watcher errors were untyped, making them invisible in reconcile logs |
| `fix(monitoring)` | Wrap dropped errors in monitoring instance handler | Monitoring reconcile handler discarded errors instead of returning them to controller-runtime, silently masking reconcile failures |
| `fix(restore)` | Allow configuring resource limits on restore job containers | Restore Jobs had no CPU or memory constraints. Pods were unschedulable in namespaces with tight resource quotas |

### Other Contributions

| Project | Contribution |
|---|---|
| [oppia/oppia](https://github.com/oppia/oppia) | Core platform stability, issue triage, and code review. Active contributor since 2026 |
| [AOSSIE-Org/EduAid](https://github.com/AOSSIE-Org/EduAid) | Resolved broken PyTorch version constraints that blocked CI across environments |
| [AOSSIE-Org/Resonate-Website](https://github.com/AOSSIE-Org/Resonate-Website) | Removed un-cleared GSAP timeline instances from React component unmount, eliminating a recurring memory leak |

---

## 🚀 Projects

| Project | What it does |
|---|---|
| [aether-core-orchestrator](https://github.com/HamidKhan1001/aether-core-orchestrator) | Backend orchestration layer at Cortexium. Runtime lifecycle, task routing, execution state |
| [30days-WebResearch](https://github.com/HamidKhan1001/30days-WebReserach) | Concurrent research engine. SSE streaming, multi-source scraping, error budget enforcement |
| [medcare-ai](https://github.com/HamidKhan1001/medcare-ai) | Medical AI application |
| [AdMatrix.ai](https://github.com/HamidKhan1001/AdMatrix.ai) | AI-powered ad targeting and campaign intelligence |
| [last30days-skill](https://github.com/HamidKhan1001/last30days-skill) | 30-day engineering practice tracker |
---

## 🏗️ Systems Design Portfolio

Production-quality implementations of distributed infrastructure components. Each covers storage, concurrency, networking, and failure recovery.

*If it doesn't page at 3 AM, you haven't built distributed systems.*

<div align="center">

| Project | System | Implementation depth |
|---|---|---|
| [blob-storage](https://github.com/HamidKhan1001/system-design-blob-storage) | Object storage (S3/MinIO internals) | XOR erasure coding, 3× replication, SHA-256 chunk integrity |
| [rate-limiter-cluster](https://github.com/HamidKhan1001/system-design-rate-limiter-cluster) | Distributed rate limiting | Atomic Lua token-bucket scripts, no race conditions across Redis nodes |
| [web-crawler](https://github.com/HamidKhan1001/system-design-web-crawler) | Scalable web crawler | Priority URL frontier, politeness delays, cryptographic content dedup |
| [search-autocomplete](https://github.com/HamidKhan1001/system-design-search-autocomplete) | Typeahead at scale | In-memory Trie, map-reduce trending aggregation, sub-30ms via CDN edge |
| [video-transcoder](https://github.com/HamidKhan1001/system-design-video-transcoder) | HLS media pipeline | 10MB chunking, concurrent async workers, broker-tracked job state |
| [chat-backbone](https://github.com/HamidKhan1001/system-design-chat-backbone) | Real-time messaging | WebSocket connection hub, heartbeat pruning, offline message queues |
| [notification-router](https://github.com/HamidKhan1001/system-design-notification-router) | Async multi-channel delivery | Exponential backoff with jitter, dead-letter queues |
| [distributed-cache](https://github.com/HamidKhan1001/system-design-distributed-cache) | In-memory KV store | O(1) LRU/LFU eviction, stampede shield, consistent-hash sharding |
| [analytics-ingestion](https://github.com/HamidKhan1001/system-design-analytics-ingestion) | Event ingestion pipeline | Kafka partitioning, Redis spike buffer, batch flushing |
| [distributed-id-generator](https://github.com/HamidKhan1001/system-design-distributed-id-generator) | Snowflake ID generation | 4,194,304 IDs/ms across 1,024 workers, clock-skew safe |

</div>

---

## 📈 GitHub Stats

<div align="center">

<img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=HamidKhan1001&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />
<img height="175" src="https://streak-stats.demolab.com?user=HamidKhan1001&theme=tokyonight&hide_border=true" />

</div>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=HamidKhan1001&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" />

</div>

<div align="center">

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=HamidKhan1001&theme=tokyo-night&hide_border=true&area=true)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=110&section=footer&animation=twinkling"/>

*Building the infrastructure layer. The part no one sees until it breaks.*

</div>
