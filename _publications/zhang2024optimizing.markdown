---
layout: publication
title: 'Revolve: Optimizing AI Systems By Tracking Response Evolution In Textual Optimization'
authors: Peiyan Zhang, Haibo Jin, Leyang Hu, Xinnuo Li, Liying Kang, Man Luo, Yangqiu Song, Haohan Wang
conference: "Arxiv"
year: 2024
bibkey: zhang2024optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.03092"}
  - {name: "Code", url: "https://github.com/Peiyance/REVOLVE"}
tags: ['Efficiency and Optimization', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Prompting']
---
Recent advancements in large language models (LLMs) have significantly
enhanced the ability of LLM-based systems to perform complex tasks through
natural language processing and tool interaction. However, optimizing these
LLM-based systems for specific tasks remains challenging, often requiring
manual interventions like prompt engineering and hyperparameter tuning.
Existing automatic optimization methods, such as textual feedback-based
techniques (e.g., TextGrad), tend to focus on immediate feedback, analogous to
using immediate derivatives in traditional numerical gradient descent. However,
relying solely on such feedback can be limited when the adjustments made in
response to this feedback are either too small or fluctuate irregularly,
potentially slowing down or even stalling the optimization process. To overcome
these challenges, more adaptive methods are needed, especially in situations
where the system's response is evolving slowly or unpredictably. In this paper,
we introduce REVOLVE, an optimization method that tracks how "R"esponses
"EVOLVE" across iterations in LLM systems. By focusing on the evolution of
responses over time, REVOLVE enables more stable and effective optimization by
making thoughtful, progressive adjustments at each step. Experimental results
demonstrate that REVOLVE outperforms competitive baselines, achieving a 7.8%
improvement in prompt optimization, a 20.72% gain in solution refinement, and a
29.17% increase in code optimization. Additionally, REVOLVE converges in fewer
iterations, resulting in significant computational savings. These advantages
highlight its adaptability and efficiency, positioning REVOLVE as a valuable
tool for optimizing LLM-based systems and accelerating the development of
next-generation AI technologies. Code is available at:
https://github.com/Peiyance/REVOLVE.
