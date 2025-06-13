---
layout: publication
title: 'Tempo: Application-aware LLM Serving With Mixed SLO Requirements'
authors: Wei Zhang, Zhiyu Wu, Yi Mu, Banruo Liu, Myungjin Lee, Fan Lai
conference: "Arxiv"
year: 2025
bibkey: zhang2025application
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.20068"}
tags: ['Agentic', 'Applications', 'Tools']
---
The integration of Large Language Models (LLMs) into diverse applications,
ranging from interactive chatbots and cloud AIOps to intelligent agents, has
introduced a wide spectrum of Service Level Objectives (SLOs) for
responsiveness. These workloads include latency-sensitive requests focused on
per-token latency in streaming chat, throughput-intensive requests that require
rapid full responses to invoke tools, and collective requests with dynamic
dependencies arising from self-reflection or agent-based reasoning. This
workload diversity, amplified by unpredictable request information such as
response lengths and runtime dependencies, makes existing schedulers inadequate
even within their design envelopes.
  In this paper, we define service gain as the useful service delivered by
completing requests. We observe that as SLO directly reflects the actual
performance needs of requests, completing a request much faster than its SLO
(e.g., deadline) yields limited additional service gain. Based on this insight,
we introduce Tempo, the first systematic SLO-aware scheduler designed to
maximize service gain across diverse LLM workloads. Tempo allocates just enough
serving bandwidth to meet each SLO, maximizing residual capacity for others
best-effort workloads. Instead of assuming request information or none at all,
it adopts a hybrid scheduling strategy: using quantile-based response upper
bounds and dependency-graph matching for conservative initial estimates,
prioritizing requests by service gain density, and refining decisions online as
generation progresses. Our evaluation across diverse workloads, including chat,
reasoning, and agentic pipelines, shows that Tempo improves end-to-end service
gain by up to 8.3\\(\times\\) and achieves up to 10.3\\(\times\\) SLO goodput compared
to state-of-the-art designs
