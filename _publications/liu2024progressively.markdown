---
layout: publication
title: 'Progressively Label Enhancement For Large Language Model Alignment'
authors: Biao Liu, Ning Xu, Xin Geng
conference: "Arxiv"
year: 2024
bibkey: liu2024progressively
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.02599'}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Prompting', 'Reinforcement Learning']
---
Large Language Models (LLM) alignment aims to prevent models from producing
content that misaligns with human expectations, which can lead to ethical and
legal concerns. In the last few years, Reinforcement Learning from Human
Feedback (RLHF) has been the most prominent method for achieving alignment. Due
to challenges in stability and scalability with RLHF stages, which arise from
the complex interactions between multiple models, researchers are exploring
alternative methods to achieve effects comparable to those of RLHF. However,
these methods often rely on large high-quality datasets. Despite some methods
considering the generation of additional data to expand datasets, they often
treat model training and data generation as separate and static processes,
overlooking the fact that these processes are highly interdependent, leading to
inefficient utilization of the generated data. To deal with this problem, we
propose PLE, i.e., Progressively Label Enhancement for LLM Alignment, a
framework that dynamically adjusts the model's training process based on the
evolving quality of the generated data. Specifically, we prompt the model to
generate responses for both the original query and the query guided by a set of
carefully designed principles, and then utilize a dynamic threshold to
determine the appropriate training approach for both responses based on their
corresponding reward scores. Experimental results demonstrate the effectiveness
of PLE compared to existing LLM alignment methods.
