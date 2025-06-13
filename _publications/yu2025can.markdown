---
layout: publication
title: 'Think: Can Large Language Models Think-aloud?'
authors: Yongan Yu, Mengqian Wu, Yiran Lin, Nikki G. Lobczowski
conference: "Arxiv"
year: 2025
bibkey: yu2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20184"}
tags: ['Agentic', 'RAG', 'Tools', 'Reinforcement Learning']
---
Assessing higher-order thinking skills in large language models (LLMs) remains a fundamental challenge, especially in tasks that go beyond surface-level accuracy. In this work, we propose THiNK (Testing Higher-order Notion of Knowledge), a multi-agent, feedback-driven evaluation framework grounded in Bloom's Taxonomy. THiNK frames reasoning assessment as an iterative task of problem generation, critique, and revision, encouraging LLMs to think-aloud through step-by-step reflection and refinement. This enables a systematic evaluation of both lower-order (e.g., remember, understand) and higher-order (e.g., evaluate, create) thinking skills. We apply THiNK to seven state-of-the-art LLMs and perform a detailed cognitive analysis of their outputs. Results reveal that while models reliably perform lower-order categories well, they struggle with applying knowledge in realistic contexts and exhibit limited abstraction. Structured feedback loops significantly improve reasoning performance, particularly in higher-order thinking. Qualitative evaluations further confirm that THiNK-guided outputs better align with domain logic and problem structure. The code of our framework provides a scalable methodology for probing and enhancing LLM reasoning, offering new directions for evaluation grounded in learning science, which is available at our GitHub repository.
