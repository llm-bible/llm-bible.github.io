---
layout: publication
title: 'Enhancing Generalization Of Speech Large Language Models With Multi-task Behavior Imitation And Speech-text Interleaving'
authors: Jingran Xie, Xiang Li, Hui Wang, Yue Yu, Yang Xiang, Xixin Wu, Zhiyong Wu
conference: "Arxiv"
year: 2025
bibkey: xie2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18644"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Large language models (LLMs) have shown remarkable generalization across tasks, leading to increased interest in integrating speech with LLMs. These speech LLMs (SLLMs) typically use supervised fine-tuning to align speech with text-based LLMs. However, the lack of annotated speech data across a wide range of tasks hinders alignment efficiency, resulting in poor generalization. To address these issues, we propose a novel multi-task 'behavior imitation' method with speech-text interleaving, called MTBI, which relies solely on paired speech and transcripts. By ensuring the LLM decoder generates equivalent responses to paired speech and text, we achieve a more generalized SLLM. Interleaving is used to further enhance alignment efficiency. We introduce a simple benchmark to evaluate prompt and task generalization across different models. Experimental results demonstrate that our MTBI outperforms SOTA SLLMs on both prompt and task generalization, while requiring less supervised speech data.
