---
layout: publication
title: 'Agentauditor: Human-level Safety And Security Evaluation For LLM Agents'
authors: Hanjun Luo, Shenyu Dai, Chiming Ni, Xinfeng Li, Guibin Zhang, Kun Wang, Tongliang Liu, Hanan Salam
conference: "Arxiv"
year: 2025
bibkey: luo2025human
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.00641"}
tags: ['Responsible AI', 'Agentic', 'Security', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG']
---
Despite the rapid advancement of LLM-based agents, the reliable evaluation of their safety and security remains a significant challenge. Existing rule-based or LLM-based evaluators often miss dangers in agents' step-by-step actions, overlook subtle meanings, fail to see how small issues compound, and get confused by unclear safety or security rules. To overcome this evaluation crisis, we introduce \sys, a universal, training-free, memory-augmented reasoning framework that empowers LLM evaluators to emulate human expert evaluators. \sys constructs an experiential memory by having an LLM adaptively extract structured semantic features (e.g., scenario, risk, behavior) and generate associated chain-of-thought reasoning traces for past interactions. A multi-stage, context-aware retrieval-augmented generation process then dynamically retrieves the most relevant reasoning experiences to guide the LLM evaluator's assessment of new cases. Moreover, we developed \data, the first benchmark designed to check how well LLM-based evaluators can spot both safety risks and security threats. \data comprises \textbf\{2293\} meticulously annotated interaction records, covering \textbf\{15\} risk types across \textbf\{29\} application scenarios. A key feature of \data is its nuanced approach to ambiguous risk situations, employing ``Strict'' and ``Lenient'' judgment standards. Experiments demonstrate that \sys not only consistently improves the evaluation performance of LLMs across all benchmarks but also sets a new state-of-the-art in LLM-as-a-judge for agent safety and security, achieving human-level accuracy. Our work is openly openly accessible.
