---
layout: publication
title: 'Scoreflow: Mastering LLM Agent Workflows Via Score-based Preference Optimization'
authors: Yinjie Wang, Ling Yang, Guohao Li, Mengdi Wang, Bryon Aragam
conference: "Arxiv"
year: 2025
bibkey: wang2025mastering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.04306"}
  - {name: "Code", url: "https://github.com/Gen-Verse/ScoreFlow"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Applications', 'RAG', 'Reinforcement Learning', 'Agent', 'Has Code']
---
Recent research has leveraged large language model multi-agent systems for
complex problem-solving while trying to reduce the manual effort required to
build them, driving the development of automated agent workflow optimization
methods. However, existing methods remain inflexible due to representational
limitations, a lack of adaptability, and poor scalability when relying on
discrete optimization techniques. We address these challenges with ScoreFlow, a
simple yet high-performance framework that leverages efficient gradient-based
optimization in a continuous space. ScoreFlow incorporates Score-DPO, a novel
variant of the direct preference optimization method that accounts for
quantitative feedback. Across six benchmarks spanning question answering,
coding, and mathematical reasoning, ScoreFlow achieves an 8.2% improvement over
existing baselines. Moreover, it empowers smaller models to outperform larger
ones with lower inference costs. Project:
https://github.com/Gen-Verse/ScoreFlow
