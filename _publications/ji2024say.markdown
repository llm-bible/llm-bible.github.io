---
layout: publication
title: 'Can''t Say Cant? Measuring And Reasoning Of Dark Jargons In Large Language Models'
authors: Xu Ji, Jianyi Zhang, Ziyin Zhou, Zhangchi Zhao, Qianqian Qiao, Kaiying Han, Md Imran Hossen, Xiali Hei
conference: "Arxiv"
year: 2024
bibkey: ji2024say
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.00718"}
  - {name: "Code", url: "https://github.com/cistineup/CantCounter"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'Model Architecture', 'Merging', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Prompting']
---
Ensuring the resilience of Large Language Models (LLMs) against malicious
exploitation is paramount, with recent focus on mitigating offensive responses.
Yet, the understanding of cant or dark jargon remains unexplored. This paper
introduces a domain-specific Cant dataset and CantCounter evaluation framework,
employing Fine-Tuning, Co-Tuning, Data-Diffusion, and Data-Analysis stages.
Experiments reveal LLMs, including ChatGPT, are susceptible to cant bypassing
filters, with varying recognition accuracy influenced by question types,
setups, and prompt clues. Updated models exhibit higher acceptance rates for
cant queries. Moreover, LLM reactions differ across domains, e.g., reluctance
to engage in racism versus LGBT topics. These findings underscore LLMs'
understanding of cant and reflect training data characteristics and vendor
approaches to sensitive topics. Additionally, we assess LLMs' ability to
demonstrate reasoning capabilities. Access to our datasets and code is
available at https://github.com/cistineup/CantCounter.
