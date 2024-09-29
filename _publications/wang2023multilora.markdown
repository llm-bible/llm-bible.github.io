---
layout: publication
title: Multilora Democratizing Lora For Better Multi-task Learning
authors: Wang Yiming, Lin Yu, Zeng Xiaodong, Zhang Guannan
conference: "Arxiv"
year: 2023
bibkey: wang2023multilora
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.11501"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
LoRA achieves remarkable resource efficiency and comparable performance when adapting LLMs for specific tasks. Since ChatGPT demonstrated superior performance on various tasks there has been a growing desire to adapt one model for all tasks. However the explicit low-rank of LoRA limits the adaptation performance in complex multi-task scenarios. LoRA is dominated by a small number of top singular vectors while fine-tuning decomposes into a set of less important unitary transforms. In this paper we propose MultiLoRA for better multi-task adaptation by reducing the dominance of top singular vectors observed in LoRA. MultiLoRA scales LoRA modules horizontally and change parameter initialization of adaptation matrices to reduce parameter dependency thus yields more balanced unitary subspaces. We unprecedentedly construct specialized training data by mixing datasets of instruction follow natural language understanding world knowledge to cover semantically and syntactically different samples. With only 2.537; of additional parameters MultiLoRA outperforms single LoRA counterparts and fine-tuning on multiple benchmarks and model scales. Further investigation into weight update matrices of MultiLoRA exhibits reduced dependency on top singular vectors and more democratic unitary transform contributions.
