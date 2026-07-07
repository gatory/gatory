<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,21,23&height=160&section=header&text=Hi%20there,%20I'm%20Kuan%20👋&fontSize=35&fontColor=ffffff&fontAlignY=35&fontAlign=52" width="100%"/>

  <div style="margin-top:-25px;">
    <a href="https://www.linkedin.com/in/kuan-wei-315b4a344/">
      <img src="https://img.shields.io/badge/LinkedIn-0057A8?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" height="35" />
    </a>
    <a href="https://kuan-code.vercel.app/">
      <img src="https://img.shields.io/badge/Portfolio-006400?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" height="35" />
    </a>
    <a href="mailto:kuandev06@gmail.com">
      <img src="https://img.shields.io/badge/Email-E0115F?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" height="35" />
    </a>
  </div>

  <br/>

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/gatory/gatory/output/github-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/gatory/gatory/output/github-snake.svg"/>
    <img alt="Contribution Snake" src="https://raw.githubusercontent.com/gatory/gatory/output/github-snake-dark.svg" width="90%"/>
  </picture>
</div>

## About

```

```

Deeply proficient in architecting end-to-end solutions — from real-time ML inference pipelines and LLM-powered product features, to scalable REST/GraphQL APIs and performant React frontends. I operate at the intersection of **engineering rigor** and **product intuition**, consistently translating ambiguous requirements into clean, maintainable systems.

My work spans model fine-tuning and evaluation, cloud-native infrastructure on AWS, microservices design, and developer tooling — always with an eye toward reliability, observability, and long-term ownership.

<br/>

**Open To:** Senior / Staff Engineering roles · AI/ML Platform · Full Stack Product · Remote-First · High-Ownership Environments

---

## Tech Stack

<div align="center">

### Languages
[![Languages](https://skillicons.dev/icons?i=python,typescript,javascript,go,java,rust,cpp,sql&theme=dark)](https://skillicons.dev)

### Frontend
[![Frontend](https://skillicons.dev/icons?i=react,nextjs,tailwind,redux,graphql,figma,html,css&theme=dark)](https://skillicons.dev)

### Backend & Databases
[![Backend](https://skillicons.dev/icons?i=nodejs,fastapi,django,postgres,mongodb,redis,kafka,elasticsearch&theme=dark)](https://skillicons.dev)

### Cloud, DevOps & Tooling
[![DevOps](https://skillicons.dev/icons?i=aws,docker,kubernetes,terraform,github,githubactions,linux,prometheus&theme=dark)](https://skillicons.dev)

</div>

---

## AI / ML Expertise

<div align="center">

| Domain | Proficiency | Details |
|:---|:---:|:---|
| Large Language Models | ██████████ Expert | GPT-4, Claude, Gemini — fine-tuning, RAG pipelines, prompt engineering |
| ML Ops & Deployment | █████████░ Advanced | MLflow, SageMaker, model versioning, A/B testing, drift detection |
| Deep Learning | █████████░ Advanced | PyTorch, Transformers, CNNs, attention mechanisms |
| Computer Vision | ████████░░ Proficient | Object detection, segmentation, CLIP, BLIP-2 |
| NLP & Text Processing | ██████████ Expert | Embeddings, semantic search, entity extraction, classification |
| Reinforcement Learning | ███████░░░ Proficient | PPO, reward modeling, RLHF alignment techniques |
| Vector Databases | █████████░ Advanced | Pinecone, Weaviate, pgvector, FAISS, hybrid search |
| Data Engineering | █████████░ Advanced | Spark, dbt, Airflow, feature stores, real-time pipelines |

</div>

---

## Featured Projects

<details>
<summary><b>⬡ &nbsp;Semantic Search Platform — Enterprise Knowledge Retrieval at Scale</b></summary>

<br/>

A production-grade semantic search and knowledge retrieval system powering enterprise document intelligence for 50,000+ concurrent users. Built with a hybrid dense-sparse retrieval architecture combining vector similarity and BM25 keyword search for sub-100ms query latency across 100M+ document chunks.

| Attribute | Detail |
|:---|:---|
| **Stack** | Python, FastAPI, React, PostgreSQL, Pinecone, OpenAI Embeddings, Redis, AWS ECS |
| **Scale** | 100M+ indexed documents · 50K concurrent users · 2M queries/day |
| **Performance** | P99 latency < 95ms · 99.95% uptime SLA · 3x faster than previous keyword search |
| **Security** | SOC 2 compliant · tenant-isolated vector namespaces · OAuth 2.0 + RBAC |
| **Impact** | Reduced support ticket volume by 38% · $1.2M ARR attributed to search feature |
| **Repository** | [![GitHub](https://img.shields.io/badge/GitHub-Private-6D28D9?style=flat-square&logo=github)](https://github.com/yourusername) |

Architected the full ingestion pipeline including document parsing, chunking strategies, embedding generation with batch optimization, and upsert orchestration. Designed the query reranking layer using a cross-encoder model, boosting relevance scores by 22% in offline evaluation. Integrated LLM-generated answer synthesis with source attribution and hallucination guardrails.

</details>

<details>
<summary><b>⬡ &nbsp;LLM Evaluation Framework — Automated Quality Assurance for AI Systems</b></summary>

<br/>

An open-source evaluation harness for systematically benchmarking LLM outputs across accuracy, coherence, groundedness, and safety dimensions. Supports multi-model comparison, regression tracking, and CI/CD integration to gate production deployments on quality thresholds.

| Attribute | Detail |
|:---|:---|
| **Stack** | Python, TypeScript, LangChain, PostgreSQL, Grafana, GitHub Actions, Docker |
| **Scale** | 200+ custom eval suites · 15 models benchmarked · 10K evaluations/run |
| **Performance** | Parallel execution reduces eval time by 74% vs sequential baseline |
| **Security** | Sandboxed eval environments · signed artifact provenance · secrets management |
| **Impact** | Adopted by 3 internal teams · prevented 6 regression deployments in first quarter |
| **Repository** | [![GitHub](https://img.shields.io/badge/GitHub-View-7C3AED?style=flat-square&logo=github)](https://github.com/yourusername/llm-eval-framework) |

Designed a pluggable metric architecture supporting custom eval functions, LLM-as-judge scoring, and human annotation workflows. Built a React dashboard for visualizing score distributions, drift alerts, and per-model regression diffs. Integrated with GitHub Actions to block merges when eval scores fall below configured thresholds.

</details>

<details>
<summary><b>⬡ &nbsp;Real-Time Analytics Pipeline — Event-Driven Data Platform</b></summary>

<br/>

A cloud-native event streaming and analytics platform processing 500M+ user events daily for a SaaS product. Delivers sub-second aggregation latency enabling real-time product dashboards, anomaly detection, and personalization signals for downstream ML models.

| Attribute | Detail |
|:---|:---|
| **Stack** | Go, Kafka, Apache Flink, ClickHouse, Terraform, Kubernetes, Grafana, AWS |
| **Scale** | 500M events/day · 6TB/day ingestion · 40+ analytics dimensions |
| **Performance** | Sub-second end-to-end latency · 10x cost reduction vs prior Redshift solution |
| **Security** | End-to-end encryption · PII tokenization · GDPR-compliant retention policies |
| **Impact** | Enabled personalization features driving 19% increase in 30-day retention |
| **Repository** | [![GitHub](https://img.shields.io/badge/GitHub-Private-6D28D9?style=flat-square&logo=github)](https://github.com/yourusername) |

Designed the Kafka topic schema and Flink job topology for stateful windowed aggregation with exactly-once semantics. Built a ClickHouse materialized view layer for low-latency OLAP queries and integrated Grafana alerting for pipeline health, consumer lag, and SLA breaches.

</details>

<details>
<summary><b>⬡ &nbsp;AI-Powered Code Review Assistant — Developer Productivity Tooling</b></summary>

<br/>

A GitHub-integrated code review assistant that provides automated, context-aware feedback on pull requests using fine-tuned LLMs trained on internal codebases. Surfaces security vulnerabilities, style deviations, and logic errors as inline GitHub annotations.

| Attribute | Detail |
|:---|:---|
| **Stack** | Python, TypeScript, FastAPI, OpenAI API, GitHub API, Redis, Celery, AWS Lambda |
| **Scale** | 1,200+ PRs reviewed/month · 8 engineering teams · 4 programming languages |
| **Performance** | Average review time < 45 seconds · 91% developer satisfaction (NPS survey) |
| **Security** | Code never leaves VPC · diff-scoped context windows · audit logging |
| **Impact** | Reduced average review turnaround from 18 hours to 3 hours · 23% fewer bugs in prod |
| **Repository** | [![GitHub](https://img.shields.io/badge/GitHub-View-7C3AED?style=flat-square&logo=github)](https://github.com/yourusername/ai-code-review) |

Fine-tuned a base model on 50K internal PR comment pairs using PEFT/LoRA for domain adaptation. Built a webhook server to process GitHub events asynchronously via Celery queues, with priority lanes for draft vs ready-for-review PRs. Implemented sliding-window context chunking to handle large diffs without exceeding token limits.

</details>

---

## Experience

<br/>

**Senior Software Engineer** &nbsp;·&nbsp; `Your Company Name` &nbsp;·&nbsp; `Jan 2023 – Present`

Owned end-to-end development and reliability of core product features serving 500K+ monthly active users. Led a 4-engineer squad on the AI Platform team, defining technical roadmap and driving cross-functional delivery from design to production.

- Designed and shipped a RAG-based customer support copilot reducing ticket deflection time by 41%
- Architected multi-tenant vector search infrastructure processing 2M+ daily queries at P99 < 100ms
- Established MLOps practices including model versioning, shadow deployments, and automated eval gating
- Mentored 3 junior engineers; conducted 50+ technical interviews and introduced structured rubrics

![Python](https://img.shields.io/badge/Python-6D28D9?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-7C3AED?style=flat-square&logo=typescript&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-8B5CF6?style=flat-square&logo=amazonaws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-4F46E5?style=flat-square&logo=kubernetes&logoColor=white)
![LLMs](https://img.shields.io/badge/LLMs-6D28D9?style=flat-square&logo=openai&logoColor=white)

<br/>

**Software Engineer** &nbsp;·&nbsp; `Previous Company Name` &nbsp;·&nbsp; `Jun 2020 – Dec 2022`

Full stack engineer on a 12-person product team building a B2B SaaS analytics platform. Contributed across the entire delivery lifecycle — from product specs to production deployments.

- Rebuilt the data ingestion pipeline in Go, reducing P99 latency from 4.2s to 380ms
- Migrated frontend from Create React App to Next.js, improving LCP by 58% and Core Web Vitals scores
- Delivered real-time WebSocket notification system handling 100K concurrent connections
- Integrated Stripe billing, reducing failed payment rate from 9.2% to 1.8% through retry logic and dunning

![Go](https://img.shields.io/badge/Go-6D28D9?style=flat-square&logo=go&logoColor=white)
![React](https://img.shields.io/badge/React-7C3AED?style=flat-square&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-8B5CF6?style=flat-square&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4F46E5?style=flat-square&logo=postgresql&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-6D28D9?style=flat-square&logo=apachekafka&logoColor=white)

---

## Achievements

<div align="center">

| Recognition | Details |
|:---:|:---|
| 🏆 &nbsp;Engineering Excellence Award | Awarded Q3 2023 for architecting the semantic search platform that became a flagship product feature |
| 🥇 &nbsp;Internal Hackathon — 1st Place | Built AI document summarization tool in 24hrs; adopted by Legal team in production |
| 📈 &nbsp;Top Contributor | Ranked #1 contributor by merged PR count for two consecutive quarters |
| 🎓 &nbsp;Dean's List — 4 Semesters | Recognized for academic excellence in Computer Science & Mathematics |
| ⭐ &nbsp;Open Source Recognition | Primary maintainer of a library with 2,400+ GitHub stars |
| 🧠 &nbsp;LeetCode Top 5% | Solved 500+ problems; Knight ranking on LeetCode weekly contests |

</div>

---

## Certifications

<div align="center">

**Amazon Web Services**

[![AWS Solutions Architect](https://img.shields.io/badge/AWS-Solutions_Architect_Professional-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://aws.amazon.com/certification/)
[![AWS ML Specialty](https://img.shields.io/badge/AWS-Machine_Learning_Specialty-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://aws.amazon.com/certification/)
[![AWS Developer](https://img.shields.io/badge/AWS-Developer_Associate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://aws.amazon.com/certification/)

<br/>

**Oracle**

[![Oracle Java](https://img.shields.io/badge/Oracle-Java_SE_Professional-F80000?style=for-the-badge&logo=oracle&logoColor=white)](https://education.oracle.com/)
[![Oracle Cloud](https://img.shields.io/badge/Oracle-Cloud_Infrastructure_Architect-F80000?style=for-the-badge&logo=oracle&logoColor=white)](https://education.oracle.com/)

<br/>

**Google / NPTEL**

[![Google ML](https://img.shields.io/badge/Google-Machine_Learning_Crash_Course-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://developers.google.com/machine-learning)
[![NPTEL](https://img.shields.io/badge/NPTEL-Deep_Learning_Elite-0052CC?style=for-the-badge&logo=coursera&logoColor=white)](https://nptel.ac.in/)
[![NPTEL DS](https://img.shields.io/badge/NPTEL-Data_Science_for_Engineers-0052CC?style=for-the-badge&logo=coursera&logoColor=white)](https://nptel.ac.in/)

<br/>

**Cisco**

[![Cisco CCNA](https://img.shields.io/badge/Cisco-CCNA_Routing_%26_Switching-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)](https://www.cisco.com/c/en/us/training-events/training-certifications/certifications.html)
[![Cisco CyberOps](https://img.shields.io/badge/Cisco-CyberOps_Associate-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)](https://www.cisco.com/c/en/us/training-events/training-certifications/certifications.html)

</div>

---

## Coding Profiles

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-500%2B_Solved_·_Knight-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/yourusername)
[![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-Institute_Rank_1-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](https://auth.geeksforgeeks.org/user/yourusername)
[![HackerRank](https://img.shields.io/badge/HackerRank-6⭐_Problem_Solving-00EA64?style=for-the-badge&logo=hackerrank&logoColor=white)](https://hackerrank.com/yourusername)
[![CodeChef](https://img.shields.io/badge/CodeChef-4★_Rating_2100%2B-5B4638?style=for-the-badge&logo=codechef&logoColor=white)](https://codechef.com/users/yourusername)

</div>

---

## GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=midnight-purple&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D0D1A&title_color=A855F7&icon_color=7C3AED&text_color=C4B5FD"/>
&nbsp;&nbsp;
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yourusername&layout=compact&langs_count=8&theme=midnight-purple&hide_border=true&bg_color=0D0D1A&title_color=A855F7&text_color=C4B5FD"/>

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=yourusername&theme=midnight-purple&hide_border=true&background=0D0D1A&stroke=6D28D9&ring=A855F7&fire=8B5CF6&currStreakLabel=C4B5FD&sideLabels=C4B5FD&dates=7C3AED&currStreakNum=A855F7&sideNums=A855F7" alt="GitHub Streak" />

</div>

---

## GitHub Trophies

<div align="center">

[![Trophy](https://github-profile-trophy.vercel.app/?username=yourusername&theme=darkhub&no-frame=true&no-bg=true&column=7&margin-w=8&title=Stars,Followers,Commits,Repositories,PullRequest,Issues,Reviews)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## Contribution Activity

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=yourusername&bg_color=0D0D1A&color=A855F7&line=7C3AED&point=C4B5FD&area=true&area_color=4F46E5&hide_border=true&custom_title=Contribution+Graph)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yourusername/yourusername/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/yourusername/yourusername/output/github-snake.svg" />
  <img alt="Contribution Snake Animation" src="https://raw.githubusercontent.com/yourusername/yourusername/output/github-snake-dark.svg" />
</picture>

</div>

---

## Current Focus

```yaml
current_focus:
  learning:
    - "Multimodal LLM architectures and vision-language alignment"
    - "Distributed systems consistency models (Raft, Paxos)"
    - "Rust for high-performance systems programming"

  building:
    - "Open-source LLM evaluation framework with CI/CD integrations"
    - "Self-hosted RAG stack with local embeddings and hybrid retrieval"
    - "Kubernetes operator for automated ML model lifecycle management"

  exploring:
    - "Agent frameworks: LangGraph, CrewAI, AutoGen"
    - "Inference optimization: quantization, speculative decoding, vLLM"
    - "eBPF for low-overhead observability in production systems"

  open_to:
    roles:
      - "Senior / Staff Software Engineer"
      - "AI/ML Platform Engineer"
      - "Full Stack Product Engineer"
    preferences:
      - "Remote-first or hybrid"
      - "High ownership, fast-moving teams"
      - "Strong engineering culture with technical leadership track"
```

---

## Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-your@email.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your@email.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-yourhandle-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourhandle)
[![GitHub](https://img.shields.io/badge/GitHub-yourusername-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yourusername)
[![Portfolio](https://img.shields.io/badge/Portfolio-yourportfolio.dev-6D28D9?style=for-the-badge&logo=vercel&logoColor=white)](https://yourportfolio.dev)

</div>

---

<div align="center">

*"The best code is no code at all — but when you must write it, write it so well it becomes invisible."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%"/>

</div>
