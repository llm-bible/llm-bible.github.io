---
layout: publication
title: 'Active Testing Of Large Language Model Via Multi-stage Sampling'
authors: Yuheng Huang, Jiayang Song, Qiang Hu, Felix Juefei-xu, Lei Ma
conference: "Arxiv"
year: 2024
bibkey: huang2024active
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.03573'}
tags: ['Reinforcement Learning', 'Tools', 'Training Techniques']
---
Performance evaluation plays a crucial role in the development life cycle of
large language models (LLMs). It estimates the model's capability, elucidates
behavior characteristics, and facilitates the identification of potential
issues and limitations, thereby guiding further improvement. Given that LLMs'
diverse task-handling abilities stem from large volumes of training data, a
comprehensive evaluation also necessitates abundant, well-annotated, and
representative test data to assess LLM performance across various downstream
tasks. However, the demand for high-quality test data often entails substantial
time, computational resources, and manual efforts, sometimes causing the
evaluation to be inefficient or impractical. To address these challenges,
researchers propose active testing, which estimates the overall performance by
selecting a subset of test data. Nevertheless, the existing active testing
methods tend to be inefficient, even inapplicable, given the unique new
challenges of LLMs (e.g., diverse task types, increased model complexity, and
unavailability of training data). To mitigate such limitations and expedite the
development cycle of LLMs, in this work, we introduce AcTracer, an active
testing framework tailored for LLMs that strategically selects a small subset
of test data to achieve a nearly optimal performance estimation for LLMs.
AcTracer utilizes both internal and external information from LLMs to guide the
test sampling process, reducing variance through a multi-stage pool-based
active selection. Our experiment results demonstrate that AcTracer achieves
state-of-the-art performance compared to existing methods across various tasks,
with up to 38.83% improvement over previous SOTA.
