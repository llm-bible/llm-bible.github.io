---
layout: publication
title: 'Teach-to-reason With Scoring: Self-explainable Rationale-driven Multi-trait Essay Scoring'
authors: Heejin Do, Sangwon Ryu, Gary Geunbae Lee
conference: "Arxiv"
year: 2025
bibkey: do2025teach
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.20748"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Ethics and Bias', 'Interpretability']
---
Multi-trait automated essay scoring (AES) systems provide a fine-grained
evaluation of an essay's diverse aspects. While they excel in scoring, prior
systems fail to explain why specific trait scores are assigned. This lack of
transparency leaves instructors and learners unconvinced of the AES outputs,
hindering their practical use. To address this, we propose a self-explainable
Rationale-Driven Multi-trait automated Essay scoring (RaDME) framework. RaDME
leverages the reasoning capabilities of large language models (LLMs) by
distilling them into a smaller yet effective scorer. This more manageable
student model is optimized to sequentially generate a trait score followed by
the corresponding rationale, thereby inherently learning to select a more
justifiable score by considering the subsequent rationale during training. Our
findings indicate that while LLMs underperform in direct AES tasks, they excel
in rationale generation when provided with precise numerical scores. Thus,
RaDME integrates the superior reasoning capacities of LLMs into the robust
scoring accuracy of an optimized smaller model. Extensive experiments
demonstrate that RaDME achieves both accurate and adequate reasoning while
supporting high-quality multi-trait scoring, significantly enhancing the
transparency of AES.
