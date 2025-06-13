---
layout: publication
title: 'Nyt-connections: A Deceptively Simple Text Classification Task That Stumps System-1 Thinkers'
authors: Angel Yahir Loredo Lopez, Tyler Mcdonald, Ali Emami
conference: "Arxiv"
year: 2024
bibkey: lopez2024nyt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.01621"}
tags: ['Prompting', 'Model Architecture', 'GPT', 'Reinforcement Learning']
---
Large Language Models (LLMs) have shown impressive performance on various
benchmarks, yet their ability to engage in deliberate reasoning remains
questionable. We present NYT-Connections, a collection of 358 simple word
classification puzzles derived from the New York Times Connections game. This
benchmark is designed to penalize quick, intuitive "System 1" thinking,
isolating fundamental reasoning skills. We evaluated six recent LLMs, a simple
machine learning heuristic, and humans across three configurations:
single-attempt, multiple attempts without hints, and multiple attempts with
contextual hints. Our findings reveal a significant performance gap: even
top-performing LLMs like GPT-4 fall short of human performance by nearly 30%.
Notably, advanced prompting techniques such as Chain-of-Thought and
Self-Consistency show diminishing returns as task difficulty increases.
NYT-Connections uniquely combines linguistic isolation, resistance to intuitive
shortcuts, and regular updates to mitigate data leakage, offering a novel tool
for assessing LLM reasoning capabilities.
