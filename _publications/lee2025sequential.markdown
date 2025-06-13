---
layout: publication
title: 'Consol: Sequential Probability Ratio Testing To Find Consistent LLM Reasoning Paths Efficiently'
authors: Jaeyeon Lee, Guantong Qi, Matthew Brady Neeley, Zhandong Liu, Hyun-hwan Jeong
conference: "Arxiv"
year: 2025
bibkey: lee2025sequential
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.17587'}
  - {name: "Code", url: 'https://github.com/LiuzLab/consol,'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Applications', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability']
---
Recent advancements in large language models (LLMs) integrating explicit
reasoning, such as OpenAI's o3-mini, DeepSeek-R1, and QWQ-32B, enable smaller
models to solve complex tasks by generating intermediate reasoning steps prior
to providing answers. However, this approach significantly increases
computational costs, both monetarily and environmentally. The widely-used
self-consistency method further exacerbates these costs by aggregating multiple
reasoning paths to improve accuracy, often requiring between 40 to 64 samples
per task. Although aggregation effectively reduces variance and bias,
additional sampling can lead to diminishing returns when early samples yield
consistent results. To address inefficiencies, we propose leveraging Sequential
Probability Ratio Testing (SPRT) to dynamically terminate sampling once
sufficient consistency is achieved. We calibrate SPRT parameters specifically
for LLM applications, accounting for sensitivity to detect the mode of the
distribution. Our experiments demonstrate that incorporating SPRT significantly
enhances token efficiency, achieving comparable accuracy to self-consistency
methods but at a substantially reduced computational cost. To promote
transparency and facilitate reproducibility, we have made the source code and
datasets used in our experiments publicly available at our GitHub repository:
https://github.com/LiuzLab/consol, or available as a PyPI package: pip install
consol. We hope that this resource will support further research and encourage
the development of new methods building upon our work.
