---
layout: publication
title: Lorahub\: Efficient Cross-task Generalization Via Dynamic Lora Composition
authors: Huang Chengsong, Liu Qian, Lin Bill Yuchen, Pang Tianyu, Du Chao, Lin Min
conference: "Arxiv"
year: 2023
bibkey: huang2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.13269"}
  - {name: "Code", url: "https://github.com/sail-sg/lorahub,"}
  - {name: "Code", url: "https://huggingface.co/lorahub"}
tags: ['Efficiency And Optimization', 'Few Shot', 'Fine Tuning', 'Has Code', 'In Context Learning', 'Prompting', 'Tools']
---
Low-rank adaptations (LoRA) are often employed to fine-tune large language models (LLMs) for new tasks. This paper investigates LoRA composability for cross-task generalization and introduces LoraHub a simple framework devised for the purposive assembly of LoRA modules trained on diverse given tasks with the objective of achieving adaptable performance on unseen tasks. With just a few examples from a new task LoraHub can fluidly combine multiple LoRA modules eliminating the need for human expertise and assumptions. Notably the composition requires neither additional model parameters nor gradients. Empirical results on the Big-Bench Hard benchmark suggest that LoraHub while not surpassing the performance of in-context learning offers a notable performance-efficiency trade-off in few-shot scenarios by employing a significantly reduced number of tokens per example during inference. Notably LoraHub establishes a better upper bound compared to in-context learning when paired with different demonstration examples demonstrating its potential for future development. Our vision is to establish a platform for LoRA modules empowering users to share their trained LoRA modules. This collaborative approach facilitates the seamless application of LoRA modules to novel tasks contributing to an adaptive ecosystem. Our code is available at https://github.com/sail-sg/lorahub, and all the pre-trained LoRA modules are released at https://huggingface.co/lorahub."
