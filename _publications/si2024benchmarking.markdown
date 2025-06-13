---
layout: publication
title: 'Design2code: Benchmarking Multimodal Code Generation For Automated Front-end Engineering'
authors: Chenglei Si, Yanzhe Zhang, Ryan Li, Zhengyuan Yang, Ruibo Liu, Diyi Yang
conference: "Arxiv"
year: 2024
bibkey: si2024benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.03163"}
tags: ['Multimodal Models', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Prompting', 'Applications']
---
Generative AI has made rapid advancements in recent years, achieving
unprecedented capabilities in multimodal understanding and code generation.
This can enable a new paradigm of front-end development in which multimodal
large language models (MLLMs) directly convert visual designs into code
implementations. In this work, we construct Design2Code - the first real-world
benchmark for this task. Specifically, we manually curate 484 diverse
real-world webpages as test cases and develop a set of automatic evaluation
metrics to assess how well current multimodal LLMs can generate the code
implementations that directly render into the given reference webpages, given
the screenshots as input. We also complement automatic metrics with
comprehensive human evaluations to validate the performance ranking. To
rigorously benchmark MLLMs, we test various multimodal prompting methods on
frontier models such as GPT-4o, GPT-4V, Gemini, and Claude. Our fine-grained
break-down metrics indicate that models mostly lag in recalling visual elements
from the input webpages and generating correct layout designs.
