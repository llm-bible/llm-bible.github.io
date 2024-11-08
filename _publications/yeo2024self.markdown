---
layout: publication
title: 'Self-training Large Language Models Through Knowledge Detection'
authors: Yeo Wei Jie, Ferdinan Teddy, Kazienko Przemyslaw, Satapathy Ranjan, Cambria Erik
conference: "Arxiv"
year: 2024
bibkey: yeo2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11275"}
tags: ['Tools', 'Training Techniques']
---
Large language models (LLMs) often necessitate extensive labeled datasets and
training compute to achieve impressive performance across downstream tasks.
This paper explores a self-training paradigm, where the LLM autonomously
curates its own labels and selectively trains on unknown data samples
identified through a reference-free consistency method. Empirical evaluations
demonstrate significant improvements in reducing hallucination in generation
across multiple subjects. Furthermore, the selective training framework
mitigates catastrophic forgetting in out-of-distribution benchmarks, addressing
a critical limitation in training LLMs. Our findings suggest that such an
approach can substantially reduce the dependency on large labeled datasets,
paving the way for more scalable and cost-effective language model training.
