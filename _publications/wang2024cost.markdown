---
layout: publication
title: 'SRSA: A Cost-efficient Strategy-router Search Agent For Real-world Human-machine Interactions'
authors: Yaqi Wang, Haipei Xu
conference: "Arxiv"
year: 2024
bibkey: wang2024cost
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.14574"}
tags: ['Fine-Tuning', 'Agentic', 'Merging', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Recently, as Large Language Models (LLMs) have shown impressive emerging
capabilities and gained widespread popularity, research on LLM-based search
agents has proliferated. In real-world situations, users often input contextual
and highly personalized queries to chatbots, challenging LLMs to capture
context and generate appropriate answers. However, much of the prior research
has not focused specifically on authentic human-machine dialogue scenarios. It
also ignores the important balance between response quality and computational
cost by forcing all queries to follow the same agent process. To address these
gaps, we propose a Strategy-Router Search Agent (SRSA), routing different
queries to appropriate search strategies and enabling fine-grained serial
searches to obtain high-quality results at a relatively low cost. To evaluate
our work, we introduce a new dataset, Contextual Query Enhancement Dataset
(CQED), comprising contextual queries to simulate authentic and daily
interactions between humans and chatbots. Using LLM-based automatic evaluation
metrics, we assessed SRSA's performance in terms of informativeness,
completeness, novelty, and actionability. To conclude, SRSA provides an
approach that resolves the issue of simple serial searches leading to
degenerate answers for lengthy and contextual queries, effectively and
efficiently parses complex user queries, and generates more comprehensive and
informative responses without fine-tuning an LLM.
