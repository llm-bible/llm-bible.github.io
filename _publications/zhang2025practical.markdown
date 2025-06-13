---
layout: publication
title: 'Practical Poisoning Attacks Against Retrieval-augmented Generation'
authors: Baolei Zhang, Yuxi Chen, Minghong Fang, Zhuqing Liu, Lihai Nie, Tong Li, Zheli Liu
conference: "Arxiv"
year: 2025
bibkey: zhang2025practical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.03957"}
tags: ['RAG', 'Security']
---
Large language models (LLMs) have demonstrated impressive natural language
processing abilities but face challenges such as hallucination and outdated
knowledge. Retrieval-Augmented Generation (RAG) has emerged as a
state-of-the-art approach to mitigate these issues. While RAG enhances LLM
outputs, it remains vulnerable to poisoning attacks. Recent studies show that
injecting poisoned text into the knowledge database can compromise RAG systems,
but most existing attacks assume that the attacker can insert a sufficient
number of poisoned texts per query to outnumber correct-answer texts in
retrieval, an assumption that is often unrealistic. To address this limitation,
we propose CorruptRAG, a practical poisoning attack against RAG systems in
which the attacker injects only a single poisoned text, enhancing both
feasibility and stealth. Extensive experiments across multiple datasets
demonstrate that CorruptRAG achieves higher attack success rates compared to
existing baselines.
