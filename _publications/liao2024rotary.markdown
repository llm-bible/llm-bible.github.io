---
layout: publication
title: '3-in-1: 2D Rotary Adaptation For Efficient Finetuning, Efficient Batching And Composability'
authors: Liao Baohao, Monz Christof
conference: "Arxiv"
year: 2024
bibkey: liao2024rotary
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.00119"}
tags: ['Applications', 'Efficiency And Optimization', 'Interpretability And Explainability', 'RAG', 'Reinforcement Learning', 'Tools']
---
"Parameter-efficient finetuning (PEFT) methods effectively adapt large language models (LLMs) to diverse downstream tasks, reducing storage and GPU memory demands. Despite these advantages, several applications pose new challenges to PEFT beyond mere parameter efficiency. One notable challenge involves the efficient deployment of LLMs equipped with multiple task- or user-specific adapters, particularly when different adapters are needed for distinct requests within the same batch. Another challenge is the interpretability of LLMs, which is crucial for understanding how LLMs function. Previous studies introduced various approaches to address different challenges. In this paper, we introduce a novel method, RoAd, which employs a straightforward 2D rotation to adapt LLMs and addresses all the above challenges: (1) RoAd is remarkably parameter-efficient, delivering optimal performance on GLUE, eight commonsense reasoning tasks and four arithmetic reasoning tasks with \(<0.1\%\) trainable parameters; (2) RoAd facilitates the efficient serving of requests requiring different adapters within a batch, with an overhead comparable to element-wise multiplication instead of batch matrix multiplication; (3) RoAd enhances LLM's interpretability through integration within a framework of distributed interchange intervention, demonstrated via composition experiments."
