---
layout: publication
title: 'Diablo: Diagonal Blocks Are Sufficient For Finetuning'
authors: Selcuk Gurses, Aozhong Zhang, Yanxia Deng, Xun Dong, Xin Li, Naigang Wang, Penghang Yin, Zi Yang
conference: "Arxiv"
year: 2025
bibkey: gurses2025diagonal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.03230"}
  - {name: "Code", url: "https://github.com/ziyangjoy/DiaBlo"}
tags: ['Fine-Tuning', 'Responsible AI', 'Efficiency and Optimization', 'Applications', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Finetuning is a critical step for adapting large language models (LLMs) to domain-specific downstream tasks. To mitigate the substantial computational and memory costs of full-model fine-tuning, Parameter-Efficient Finetuning (PEFT) methods have been proposed to update only a small subset of model parameters. However, performance gaps between PEFT approaches and full-model fine-tuning still exist. In this work, we present DiaBlo, a simple yet effective PEFT approach that updates only the diagonal blocks of selected model weight matrices. Unlike Low Rank Adaptation (LoRA) and its variants, DiaBlo eliminates the need for low rank matrix products, thereby avoiding the reliance on auxiliary initialization schemes or customized optimization strategies to improve convergence. This design leads to stable and robust convergence while maintaining comparable memory efficiency and training speed to LoRA. We conduct extensive experiments across a range of tasks, including commonsense reasoning, arithmetic reasoning, code generation, and safety alignment, to evaluate the effectiveness and efficiency of DiaBlo. Across these benchmarks, DiaBlo demonstrates strong and consistent performance while maintaining high memory efficiency and fast finetuning speed. Codes are available at https://github.com/ziyangjoy/DiaBlo.
