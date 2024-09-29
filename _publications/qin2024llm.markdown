---
layout: publication
title: "Diffusiongpt: Llm-driven Text-to-image Generation System"
authors: Qin Jie, Wu Jie, Chen Weifeng, Ren Yuxi, Li Huixia, Wu Hefeng, Xiao Xuefeng, Wang Rui, Wen Shilei
conference: "Arxiv"
year: 2024
bibkey: qin2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.10061"}
tags: ['GPT', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
Diffusion models have opened up new avenues for the field of image generation resulting in the proliferation of high-quality models shared on open-source platforms. However a major challenge persists in current text-to-image systems are often unable to handle diverse inputs or are limited to single model results. Current unified attempts often fall into two orthogonal aspects i) parse Diverse Prompts in input stage; ii) activate expert model to output. To combine the best of both worlds we propose DiffusionGPT which leverages Large Language Models (LLM) to offer a unified generation system capable of seamlessly accommodating various types of prompts and integrating domain-expert models. DiffusionGPT constructs domain-specific Trees for various generative models based on prior knowledge. When provided with an input the LLM parses the prompt and employs the Trees-of-Thought to guide the selection of an appropriate model thereby relaxing input constraints and ensuring exceptional performance across diverse domains. Moreover we introduce Advantage Databases where the Tree-of-Thought is enriched with human feedback aligning the model selection process with human preferences. Through extensive experiments and comparisons we demonstrate the effectiveness of DiffusionGPT showcasing its potential for pushing the boundaries of image synthesis in diverse domains.
