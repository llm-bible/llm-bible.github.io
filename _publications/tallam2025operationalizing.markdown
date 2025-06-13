---
layout: publication
title: 'Operationalizing Camel: Strengthening LLM Defenses For Enterprise Deployment'
authors: Krti Tallam, Emma Miller
conference: "Arxiv"
year: 2025
bibkey: tallam2025operationalizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22852"}
tags: ['Agentic', 'Security', 'Reinforcement Learning', 'RAG', 'Prompting']
---
CaMeL (Capabilities for Machine Learning) introduces a capability-based sandbox to mitigate prompt injection attacks in large language model (LLM) agents. While effective, CaMeL assumes a trusted user prompt, omits side-channel concerns, and incurs performance tradeoffs due to its dual-LLM design. This response identifies these issues and proposes engineering improvements to expand CaMeL's threat coverage and operational usability. We introduce: (1) prompt screening for initial inputs, (2) output auditing to detect instruction leakage, (3) a tiered-risk access model to balance usability and control, and (4) a verified intermediate language for formal guarantees. Together, these upgrades align CaMeL with best practices in enterprise security and support scalable deployment.
