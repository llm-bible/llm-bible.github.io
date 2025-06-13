---
layout: publication
title: 'Rethinking Chain-of-thought From The Perspective Of Self-training'
authors: Zongqian Wu, Baoduo Xu, Ruochen Cui, Mengmeng Zhan, Xiaofeng Zhu, Lei Feng
conference: "Arxiv"
year: 2024
bibkey: wu2024rethinking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.10827'}
tags: ['RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Prompting']
---
Chain-of-thought (CoT) reasoning has emerged as an effective approach for activating latent capabilities in LLMs. Interestingly, we observe that both CoT reasoning and self-training share the core objective: iteratively leveraging model-generated information to progressively reduce prediction uncertainty. Building on this insight, we propose a novel CoT framework to improve reasoning performance. Our framework integrates two key components: (i) a task-specific prompt module that optimizes the initial reasoning process, and (ii) an adaptive reasoning iteration module that dynamically refines the reasoning process and addresses the limitations of previous CoT approaches, \ie over-reasoning and high similarity between consecutive reasoning iterations. Extensive experiments demonstrate that the proposed method achieves significant advantages in both performance and computational efficiency.
