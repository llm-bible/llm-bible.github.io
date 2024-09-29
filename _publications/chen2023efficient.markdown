---
layout: publication
title: Lorashear Efficient Large Language Model Structured Pruning And Knowledge Recovery
authors: Chen Tianyi, Ding Tianyu, Yadav Badal, Zharkov Ilya, Liang Luming
conference: "Arxiv"
year: 2023
bibkey: chen2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.18356"}
  - {name: "Code", url: "https://github.com/microsoft/lorashear"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'Pruning', 'Training Techniques']
---
Large Language Models (LLMs) have transformed the landscape of artificial intelligence while their enormous size presents significant challenges in terms of computational costs. We introduce LoRAShear a novel efficient approach to structurally prune LLMs and recover knowledge. Given general LLMs LoRAShear at first creates the dependency graphs over LoRA modules to discover minimally removal structures and analyze the knowledge distribution. It then proceeds progressive structured pruning on LoRA adaptors and enables inherent knowledge transfer to better preserve the information in the redundant structures. To recover the lost knowledge during pruning LoRAShear meticulously studies and proposes a dynamic fine-tuning schemes with dynamic data adaptors to effectively narrow down the performance gap to the full models. Numerical results demonstrate that by only using one GPU within a couple of GPU days LoRAShear effectively reduced footprint of LLMs by 2037; with only 1.037; performance degradation and significantly outperforms state-of-the-arts. The source code will be available at https://github.com/microsoft/lorashear.
