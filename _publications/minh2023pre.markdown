---
layout: publication
title: PRE Vision-Language Prompt Learning with Reparameterization Encoder
authors: Minh Anh Pham Thi, Nguyen An Duc, Tzimiropoulos Georgios
conference: "Arxiv"
year: 2023
bibkey: minh2023pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.07760"}
tags: ['Efficiency And Optimization', 'Few Shot', 'Fine Tuning', 'Multimodal Models', 'Prompting', 'RAG', 'Training Techniques']
---
Large pre-trained vision-language models such as CLIP have demonstrated great potential in zero-shot transferability to downstream tasks. However to attain optimal performance the manual selection of prompts is necessary to improve alignment between the downstream image distribution and the textual class descriptions. This manual prompt engineering is the major challenge for deploying such models in practice since it requires domain expertise and is extremely time-consuming. To avoid non-trivial prompt engineering recent work Context Optimization (CoOp) introduced the concept of prompt learning to the vision domain using learnable textual tokens. While CoOp can achieve substantial improvements over manual prompts its learned context is worse generalizable to wider unseen classes within the same dataset. In this work we present Prompt Learning with Reparameterization Encoder (PRE) - a simple and efficient method that enhances the generalization ability of the learnable prompt to unseen classes while maintaining the capacity to learn Base classes. Instead of directly optimizing the prompts PRE employs a prompt encoder to reparameterize the input prompt embeddings enhancing the exploration of task-specific knowledge from few-shot samples. Experiments and extensive ablation studies on 8 benchmarks demonstrate that our approach is an efficient method for prompt learning. Specifically PRE achieves a notable enhancement of 5.60 in average accuracy on New classes and 3 in Harmonic mean compared to CoOp in the 16-shot setting all achieved within a good training time.
