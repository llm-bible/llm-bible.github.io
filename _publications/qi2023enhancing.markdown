---
layout: publication
title: PILLOW Enhancing Efficient Instruction Fine45;tuning Via Prompt Matching
authors: Qi Zhenting, Tan Xiaoyu, Shi Shaojie, Qu Chao, Xu Yinghui, Qi Yuan
conference: "Arxiv"
year: 2023
bibkey: qi2023enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.05621"}
tags: ['Agentic', 'Fine Tuning', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Instruction fine45;tuning has conventionally been employed to adapt Large Language Models (LLMs) to a variety of tasks. Nonetheless this technique often necessitates substantial computational resources making it impractical for deployment by individuals or small45;scale entities. Recently Low45;Rank Adaptation (LoRA) has become a promising alternative offering high capabilities on par with full tuning with reduced resource overhead. However attaining satisfactory performance through the fine45;tuning of LoRA is a non45;trivial challenge. In this paper we propose PILLOW which aims to improve LoRAs performance by a discrimination45;based prompting method leveraging LLMs In45;Context Learning ability. PILLOW incorporates a matching network that selects prompts from a user45;defined prompt pool concatenates the selected prompts with the user instruction as input and performs inference using the LoRA45;fine45;tuned LLMs. Trained with Reinforcement Learning PILLOW exhibits commensurate performance on various evaluation metrics compared with typical instruction fine45;tuning methods utilizing only consumer45;grade GPU resources and exhibiting a large reduction in computational costs.
