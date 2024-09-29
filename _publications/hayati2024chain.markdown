---
layout: publication
title: Chain-of-instructions\: Compositional Instruction Tuning On Large Language Models
authors: Hayati Shirley Anugrah, Jung Taehee, Bodding-long Tristan, Kar Sudipta, Sethy Abhinav, Kim Joo-kyung, Kang Dongyeop
conference: "Arxiv"
year: 2024
bibkey: hayati2024chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11532"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Fine-tuning large language models (LLMs) with a collection of large and diverse instructions has improved the models generalization to different tasks even for unseen tasks. However most existing instruction datasets include only single instructions and they struggle to follow complex instructions composed of multiple subtasks. In this work we propose a novel concept of compositional instructions called chain-of-instructions (CoI) where the output of one instruction becomes an input for the next like a chain. Unlike the conventional practice of solving single instruction tasks our proposed method encourages a model to solve each subtask step by step until the final answer is reached. CoI-tuning (i.e. fine-tuning with CoI instructions) improves the models ability to handle instructions composed of multiple subtasks as well as unseen composite tasks such as multilingual summarization. Overall our study find that simple CoI tuning of existing instruction data can provide consistent generalization to solve more complex unseen and longer chains of instructions.
