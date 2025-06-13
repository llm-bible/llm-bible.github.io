---
layout: publication
title: 'The Browsergym Ecosystem For Web Agent Research'
authors: Thibault Le Sellier De Chezelles, Maxime Gasse, Alexandre Drouin, Massimo Caccia, Léo Boisvert, Megh Thakkar, Tom Marty, Rim Assouel, Sahar Omidi Shayegan, Lawrence Keunho Jang, Xing Han Lù, Ori Yoran, Dehan Kong, Frank F. Xu, Siva Reddy, Quentin Cappart, Graham Neubig, Ruslan Salakhutdinov, Nicolas Chapados, Alexandre Lacoste
conference: "Arxiv"
year: 2024
bibkey: dechezelles2024browsergym
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.05467'}
tags: ['Agentic', 'RAG', 'Model Architecture', 'GPT', 'Tools', 'Reinforcement Learning']
---
The BrowserGym ecosystem addresses the growing need for efficient evaluation
and benchmarking of web agents, particularly those leveraging automation and
Large Language Models (LLMs). Many existing benchmarks suffer from
fragmentation and inconsistent evaluation methodologies, making it challenging
to achieve reliable comparisons and reproducible results. In an earlier work,
Drouin et al. (2024) introduced BrowserGym which aims to solve this by
providing a unified, gym-like environment with well-defined observation and
action spaces, facilitating standardized evaluation across diverse benchmarks.
We propose an extended BrowserGym-based ecosystem for web agent research, which
unifies existing benchmarks from the literature and includes AgentLab, a
complementary framework that aids in agent creation, testing, and analysis. Our
proposed ecosystem offers flexibility for integrating new benchmarks while
ensuring consistent evaluation and comprehensive experiment management. As a
supporting evidence, we conduct the first large-scale, multi-benchmark web
agent experiment and compare the performance of 6 state-of-the-art LLMs across
6 popular web agent benchmarks made available in BrowserGym. Among other
findings, our results highlight a large discrepancy between OpenAI and
Anthropic's latests models, with Claude-3.5-Sonnet leading the way on almost
all benchmarks, except on vision-related tasks where GPT-4o is superior.
Despite these advancements, our results emphasize that building robust and
efficient web agents remains a significant challenge, due to the inherent
complexity of real-world web environments and the limitations of current
models.
