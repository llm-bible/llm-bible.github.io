---
layout: publication
title: 'PILLOW: Enhancing Efficient Instruction Fine-tuning Via Prompt Matching'
authors: Zhenting Qi, Xiaoyu Tan, Shaojie Shi, Chao Qu, Yinghui Xu, Yuan Qi
conference: "Arxiv"
year: 2023
bibkey: qi2023enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.05621"}
tags: ['Fine-Tuning', 'Agentic', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Instruction fine-tuning has conventionally been employed to adapt Large
Language Models (LLMs) to a variety of tasks. Nonetheless, this technique often
necessitates substantial computational resources, making it impractical for
deployment by individuals or small-scale entities. Recently, Low-Rank
Adaptation (LoRA) has become a promising alternative, offering high
capabilities on par with full tuning with reduced resource overhead. However,
attaining satisfactory performance through the fine-tuning of LoRA is a
non-trivial challenge. In this paper, we propose PILLOW, which aims to improve
LoRA's performance by a discrimination-based prompting method, leveraging LLMs'
In-Context Learning ability. PILLOW incorporates a matching network that
selects prompts from a user-defined prompt pool, concatenates the selected
prompts with the user instruction as input, and performs inference using the
LoRA-fine-tuned LLMs. Trained with Reinforcement Learning, PILLOW exhibits
commensurate performance on various evaluation metrics compared with typical
instruction fine-tuning methods, utilizing only consumer-grade GPU resources
and exhibiting a large reduction in computational costs.
