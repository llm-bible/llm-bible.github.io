---
layout: publication
title: 'Adaptive Task Vectors For Large Language Models'
authors: Joonseong Kang, Soojeong Lee, Subeen Park, Sumin Park, Taero Kim, Jihee Kim, Ryunyi Lee, Kyungwoo Song
conference: "Arxiv"
year: 2025
bibkey: kang2025adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.03426"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
In-Context Learning (ICL) enables Large Language Models (LLMs) to perform tasks without parameter updates by conditioning on a few demonstrations provided in the prompt. Despite its success, ICL suffers from several limitations, including sensitivity to demonstration order, context length constraints, and computational inefficiency. To address these challenges, task vector-based approaches compress task information into a single vector. However, these methods typically construct task vectors from fixed sets of demonstrations and reuse them across input queries, without conditioning on the specific input. This limitation can lead models to struggle with effective adaptation when the input query is not well aligned with the underlying demonstrations, consequently degrading their generalization performance on unseen tasks. To overcome this limitation, we propose Adaptive Task Vectors (ATV), a simple and effective framework that dynamically generates task vectors conditioned on each input query. ATV employs a small language model to generate task vectors, which are then transformed to match the target LLM's architecture and applied to guide its output generation. In contrast to ICL and previous vector-based approaches, which rely on fixed demonstration sets and their corresponding vectors, ATV dynamically generates task vectors tailored to each specific input query and task. Consequently, ATV demonstrates strong performance and generalization capabilities, even for unseen tasks. Furthermore, we provide a theoretical analysis indicating that ATV is expressively equivalent to LoRA under equal rank budgets and more expressive than Prefix-Tuning, thereby offering formal support for its representational advantage.
