---
layout: publication
title: Critique Ability Of Large Language Models
authors: Luo Liangchen, Lin Zi, Liu Yinxiao, Shu Lei, Zhu Yun, Shang Jingbo, Meng Lei
conference: "Arxiv"
year: 2023
bibkey: luo2023critique
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.04815"}
tags: ['Applications', 'Fine Tuning', 'RAG', 'Reinforcement Learning', 'Tools']
---
Critical thinking is essential for rational decision-making and problem-solving. This skill hinges on the ability to provide precise and reasoned critiques and is a hallmark of human intelligence. In the era of large language models (LLMs) this study explores the ability of LLMs to deliver accurate critiques across various tasks. We are interested in this topic as a capable critic model could not only serve as a reliable evaluator but also as a source of supervised signals for model tuning. Particularly if a model can self-critique it has the potential for autonomous self-improvement. To examine this we introduce a unified evaluation framework for assessing the critique abilities of LLMs. We develop a benchmark called CriticBench which comprises 3K high-quality natural language queries and corresponding model responses; and annotate the correctness of these responses. The benchmark cover tasks such as math problem-solving code completion and question answering. We evaluate multiple LLMs on the collected dataset and our analysis reveals several noteworthy insights (1) Critique is generally challenging for most LLMs and this capability often emerges only when models are sufficiently large. (2) In particular self-critique is especially difficult. Even top-performing LLMs struggle to achieve satisfactory performance. (3) Models tend to have lower critique accuracy on problems where they are most uncertain. To this end we introduce a simple yet effective baseline named self-check which leverages self-critique to improve task performance for various models. We hope this study serves as an initial exploration into understanding the critique abilities of LLMs and aims to inform future research including the development of more proficient critic models and the application of critiques across diverse tasks.
