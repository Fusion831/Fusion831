# Hi, I'm Daksh.

Growing up, my main drive was simple: I wanted to be someone people could rely on.
When I got into technology, I carried that instinct with me. Engineering felt like the most direct way to make a real impact. The more I built, though, the more I realized a harsh truth:
> Impact doesn't matter if the systems behind it collapse the moment they encounter real-world scale.
That realization is what pulled me toward backend systems, distributed architectures, and AI infrastructure. I'm less interested in demos that work once and more interested in understanding why systems fail, how they recover, and what trade-offs exist between speed, reliability, and complexity.
---
# What I'm Building
## AI Nervous System

One of the projects I'm currently working on is what I think of as an AI Nervous System: a durable execution engine for long-running AI workflows.
Most AI products focus on the model. I'm interested in the runtime around it.
The goal is to treat AI outputs as executable workflows rather than simple prompt-response interactions, using state machines, event streams, distributed workers, and checkpoint recovery so that a failure late in execution doesn't force the entire system to start over.

## MemoryCRM

Alongside that, I've been experimenting with MemoryCRM, an attempt to solve a problem I keep noticing among founders and operators.
Opportunities are rarely lost because someone forgot to send an email. They're lost because context becomes fragmented across conversations, tools, and human memory.
The idea is simple:
> AI extracts facts. Code makes decisions.
---
# Previous Systems

## RakshaSaathi

RakshaSaathi began with a very human problem: helping families remotely monitor elderly relatives without living in constant anxiety about unseen emergencies.
What interested me most wasn't the machine learning itself, but the infrastructure required to keep the system responsive under load. To avoid inference workloads blocking ingestion, I separated the ML pipeline from the event stream using Go, FastAPI, and NATS JetStream.
The system sustained roughly **700 events per second** under simulated backpressure while maintaining low latency.
**Repository:**
https://github.com/Fusion831/RakshaSaathi
---

## AtomQuest

AtomQuest was built during the Atomberg Hackathon.
The challenge wasn't scaling throughput but preserving context. The project focused on helping employees and HR teams track growth over time without relying on fragmented spreadsheets and disconnected documents.
Building it taught me a lot about designing systems that remain simple for users while staying maintainable underneath.
**National Finalist - Atomberg Hackathon**
**Demo:**
https://atom-berg-hackathon.vercel.app/login
---
## LogiScale

LogiScale started entirely out of curiosity.
I wanted to understand how routing systems actually work without hiding behind abstractions. That curiosity led me into spatial indexing, QuadTrees, A* search, and eventually building a distributed routing engine in Go.
**Repository:**
https://github.com/Fusion831/Distributed-Delivery-Routing-Engine

## AlphaLab

Currently Research is being bombarded well with research papers, and people cant go through them quickly enough, While I did my own research I realised this, so in a Google Deepmind Hackathon, I built an app that analyzes Research papers, breaks them into structured components, analyzes for inconsistencies, finds gaps, as well allows you to compare two research papers 
on their methodology, results, why they happened etc.
**Deployed Link**: https://ai.studio/apps/drive/1m_MydeDoWDlZ22xgRLHgTFk7DREAoK53?fullscreenApplet=true
---
# Research
## Type 2 Diabetes Prediction
Outside of building systems, I work as an undergraduate researcher on Type 2 Diabetes prediction.
What interests me isn't achieving the highest benchmark score. It's understanding how models behave closer to deployment.
Clinical ML has taught me that metrics can be misleading, false negatives carry real-world consequences, and reliability matters just as much as accuracy.
Current areas of focus include:
* Feature engineering using surrogate biomarkers
* Generalization-focused evaluation
* F2-Score optimization
* Robust validation through Stratified Cross Validation
---
# How I Think
> Systems don't fail at average load. They fail at the edges.
> Bottlenecks matter more than peak performance.
> AI is a component within a larger system, not the system itself.
> Reliability is rarely something you add later. It has to be designed in from the beginning.
---
# Tech
**Backend & Infrastructure**
Python • Go • FastAPI • PostgreSQL • Redis • Docker • NATS JetStream
**AI & Search**
LangGraph • Qdrant • Pinecone • PyTorch • XGBoost
---
# Currently Reading
* *Designing Data-Intensive Applications*
* *So Good They Can't Ignore You*
* *Percy Jackson* (for sanity)
---

# Looking For
I'm currently looking for:
* Backend Engineering Internships
* AI Infrastructure Internships
* Distributed Systems Projects
* Early-stage startups solving difficult technical problems

I'm especially interested in systems that operate under real-world constraints rather than ideal conditions.
If you're building something challenging, interesting, or slightly unreasonable, I'd be happy to talk.
---
# Reach Me
**LinkedIn**
https://linkedin.com/in/daksh-b3a435323
**Email**
[dakshdaksh698@gmail.com](mailto:dakshdaksh698@gmail.com)
