---
layout: publication
title: 'Finger: Content Aware Fine-grained Evaluation With Reasoning For Ai-generated Videos'
authors: Rui Chen, Lei Sun, Jing Tang, Geng Li, Xiangxiang Chu
conference: "Arxiv"
year: 2025
bibkey: chen2025content
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.10358'}
tags: ['RAG', 'Efficiency and Optimization', 'Applications', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Recent advances in video generation have posed great challenges in the
assessment of AI-generated content, particularly with the emergence of
increasingly sophisticated models. The various inconsistencies and defects
observed in such videos are inherently complex, making overall scoring
notoriously difficult. In this paper, we emphasize the critical importance of
integrating fine-grained reasoning into video evaluation, and we propose
\\(\textbf\{F\}\\)ing\\(\textbf\{ER\}\\), a novel entity-level reasoning evaluation
framework that first automatically generates \\(\textbf\{F\}\\)ine-grained
\\(\textbf\{E\}\\)ntity-level questions, and then answers those questions by a
\\(\textbf\{R\}\\)easoning model with scores, which can be subsequently weighted
summed to an overall score for different applications. Specifically, we
leverage LLMs to derive entity-level questions across five distinct
perspectives, which (i) often focus on some specific entities of the content,
thereby making answering or scoring much easier by MLLMs, and (ii) are more
interpretable. Then we construct a FingER dataset, consisting of approximately
3.3k videos and corresponding 60k fine-grained QA annotations, each with
detailed reasons. Based on that, we further investigate various training
protocols to best incentivize the reasoning capability of MLLMs for correct
answer prediction. Extensive experiments demonstrate that a reasoning model
trained using Group Relative Policy Optimization (GRPO) with a cold-start
strategy achieves the best performance. Notably, our model surpasses existing
methods by a relative margin of \\(11.8%\\) on GenAI-Bench and \\(5.5%\\) on
MonetBench with only 3.3k training videos, which is at most one-tenth of the
training samples utilized by other methods. Our code and dataset will be
released soon.
