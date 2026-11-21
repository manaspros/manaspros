<a href="https://manaschoudhary.dev"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/hero-dark.svg"><img alt="Manas Choudhary. I build and run the systems behind AI agents that do real engineering work. Seeking a Software Engineering Internship." src="./assets/hero-light.svg" width="100%"></picture></a>

<p align="center">
  <a href="https://manaschoudhary.dev"><b>manaschoudhary.dev</b></a> &nbsp;·&nbsp;
  <a href="https://manaschoudhary.dev/work">Work timeline</a> &nbsp;·&nbsp;
  <a href="mailto:manas24102@iiitnr.edu.in">manas24102@iiitnr.edu.in</a> &nbsp;·&nbsp;
  <a href="https://linkedin.com/in/-manas-choudhary-">LinkedIn</a>
</p>

<a href="https://manaschoudhary.dev/work"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/factory-dark.svg"><img alt="Inside the software factory, with the parts I owned marked: session recovery, sandbox crash recovery, the security reviewer, automatic evals and a cost audit. Agent run success went from 40-50% to 90%+ after the reliability sprint I led." src="./assets/factory-light.svg" width="100%"></picture></a>

<a href="https://github.com/manaspros/qengine"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/qengine-dark.svg"><img alt="qengine, my from-scratch CUDA inference engine: 116.8 tokens per second at batch 1 on one RTX 5090, 93.8% of the memory-bandwidth roofline, 1.36x llama.cpp; 250 tokens per second with exact speculative decoding." src="./assets/qengine-light.svg" width="100%"></picture></a>

### Where I went deep

<p align="center">
<picture><source media="(prefers-color-scheme: dark)" srcset="./assets/card-reliability-dark.svg"><img alt="Distributed systems. Agents died mid-run and nothing noticed. Pods died mid-dispatch and left sessions marked active forever. I checked 927 flagged rows against GitHub: 921 were real failures, 358 from one cause. Shipped orphan recovery, a liveness watchdog and deploy-safe resume. Result: 40–50% → 90%+ agent run success after the sprint I led." src="./assets/card-reliability-light.svg" width="49%"></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="./assets/card-security-dark.svg"><img alt="Long-running agents. Every pull request needs a security review. I own the AI security reviewer that runs on every PR. It could load only 10 of its 21 security reference docs; I fixed the routing, paging past 100 files, and a cost cap that existed only in prose. Result: 22,000+ reviews dispatched, on by default in about 300 repos." src="./assets/card-security-light.svg" width="49%"></picture>
</p>
<p align="center">
<picture><source media="(prefers-color-scheme: dark)" srcset="./assets/card-evals-dark.svg"><img alt="Evaluation. Which model should judge a security finding?. Built an eval of 302 human-labelled findings that re-runs blind at every commit, and tested six judge models. When one gate scored 72% offline but 8% live, I published the live number. Result: 74 of 75 false positives stopped by the best judge, offline." src="./assets/card-evals-light.svg" width="49%"></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="./assets/card-dashboard-dark.svg"><img alt="Observability. The dashboard everyone trusted was wrong. It showed 59.6% run success. I traced it run by run and added a bounded retry for dying runs. Separately, 171 of 235 failures labelled model stalls were really a spending cap; I split them into honest outcomes. Result: 89% the real success rate, not 59.6%." src="./assets/card-dashboard-light.svg" width="49%"></picture>
</p>
<p align="center">
<picture><source media="(prefers-color-scheme: dark)" srcset="./assets/card-support-dark.svg"><img alt="Support automation. Support cases waited more than a week. Built the pipeline that hands Zendesk cases to an investigating agent, as part of the team&#x27;s push on time to resolve. The platform has now run 3,500+ support investigations. Result: 8.1 → 4.4 days team median time to resolve." src="./assets/card-support-light.svg" width="49%"></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="./assets/card-registry-dark.svg"><img alt="Registry and cost. Skills silently vanished on sync. On the agent and skill registry, I found two separate bugs dropping 3 of 69 skills, and shipped 15 fixes in the pre-launch bugbash, one a security bug. I also traced 72% of scheduled LLM spend to one pipeline. Result: 72% of scheduled LLM spend traced to one pipeline." src="./assets/card-registry-light.svg" width="49%"></picture>
</p>

<picture><source media="(prefers-color-scheme: dark)" srcset="./assets/beyond-dark.svg"><img alt="Research at IIT Roorkee (paper under review at ACL Rolling Review), co-founder of Sigmoyd (400+ customers), Figma-to-React agent at Samsung R&amp;D." src="./assets/beyond-light.svg" width="100%"></picture>

<a href="https://manaschoudhary.dev/projects/agent-os"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/agentos-dark.svg"><img alt="AgentOS: every AI agent breaks somewhere between build, ship and improve; AgentOS fixes all three behind one URL." src="./assets/agentos-light.svg" width="100%"></picture></a>

<p align="center">
  <a href="https://youtu.be/I9KVPHxZsVw"><b>Watch the AgentOS demo</b></a> &nbsp;·&nbsp;
  <a href="https://manaschoudhary.dev/projects/agent-os">Architecture</a> &nbsp;·&nbsp;
  <a href="https://manaschoudhary.dev/projects/agent-os/incidents">Incident write-ups</a> &nbsp;·&nbsp;
  <a href="https://govrix.dev">Govrix</a> &nbsp;·&nbsp;
  <a href="https://github.com/manaspros/chunkscope">ChunkScope</a>
</p>

### What I work with

| | |
|---|---|
| **Languages** | Python, TypeScript, Rust, Go, C++, CUDA, SQL |
| **Agents and LLMs** | LangGraph, multi-agent systems, MCP, Claude Agent SDK, LLM evaluation (LLM-as-judge, RAGAS), RAG, hybrid search (BM25, pgvector), vLLM, speculative decoding, KV cache and paged attention, Triton, PyTorch, Hugging Face |
| **Backend and distributed systems** | FastAPI, Node.js, Celery, Tokio, WebSockets, event-driven systems, API gateways, session recovery, rate limiting |
| **Data** | PostgreSQL, pgvector, Redis, TimescaleDB, DynamoDB, MongoDB |
| **Infrastructure** | AWS, Kubernetes, Docker, Cloudflare Workers and Durable Objects, Prometheus, Grafana, OpenTelemetry, CI/CD |

<sub>1st place, Hack-a-Sol 2025 (AI/ML track) &nbsp;·&nbsp; Rank 9, Amazon ML Challenge 2026 &nbsp;·&nbsp; B.Tech Data Science and AI, IIIT Naya Raipur</sub>

<p align="center"><img src="https://komarev.com/ghpvc/?username=manaspros&color=d9480f&style=flat-square&label=PROFILE+VIEWS" alt="Profile views"></p>
