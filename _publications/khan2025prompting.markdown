---
layout: publication
title: 'ORAL: Prompting Your Large-scale Loras Via Conditional Recurrent Diffusion'
authors: Rana Muhammad Shahroz Khan, Dongwen Tang, Pingzhi Li, Kai Wang, Tianlong Chen
conference: "Arxiv"
year: 2025
bibkey: khan2025prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.24354"}
tags: ['Fine-Tuning', 'Tools', 'Model Architecture', 'Merging', 'Training Techniques', 'Multimodal Models', 'Prompting']
---
Parameter generation has emerged as a novel paradigm for neural network
development, offering an alternative to traditional neural network training by
synthesizing high-quality model weights directly. In the context of Low-Rank
Adaptation (LoRA) for evolving (\\(\textit\{i.e.\}\\), constantly updated) large
language models (LLMs), this approach promises efficient adaptation without
costly retraining. However, existing methods face critical limitations in
simultaneously achieving scalability and controllability. In this paper, we
introduce \\(\texttt\{ORAL\}\\), a novel \\(\textbf\{conditional recurrent diffusion\}\\)
framework that addresses these challenges. \\(\texttt\{ORAL\}\\) incorporates a novel
conditioning mechanism that integrates model architecture and textual task
specifications, enabling the generation of task-specific LoRA parameters that
can seamlessly transfer across evolving foundation models. Our approach
successfully scales to billions-of-parameter LLMs and maintains
controllability. Through extensive experiments across seven language tasks,
four vision tasks, and three multimodal tasks using five pre-trained LLMs, we
demonstrate that \\(\texttt\{ORAL\}\\) generates high-quality LoRA parameters that
achieve comparable or superior performance to vanilla trained counterparts.
