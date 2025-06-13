---
layout: publication
title: 'PAFT: Prompt-agnostic Fine-tuning'
authors: Chenxing Wei, Yao Shu, Mingwen Ou, Ying Tiffany He, Fei Richard Yu
conference: "Arxiv"
year: 2025
bibkey: wei2025prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12859"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
While Large Language Models (LLMs) adapt well to downstream tasks after
fine-tuning, this adaptability often compromises prompt robustness, as even
minor prompt variations can significantly degrade performance. To address this,
we propose Prompt-Agnostic Fine-Tuning(PAFT), a simple yet effective approach
that dynamically adjusts prompts during fine-tuning. This encourages the model
to learn underlying task principles rather than overfitting to specific prompt
formulations. PAFT operates in two stages: First, a diverse set of meaningful,
synthetic candidate prompts is constructed. Second, during fine-tuning, prompts
are randomly sampled from this set to create dynamic training inputs. Extensive
experiments across diverse datasets and LLMs demonstrate that models trained
with PAFT exhibit strong robustness and generalization across a wide range of
prompts, including unseen ones. This enhanced robustness improves both model
performance and inference speed while maintaining training efficiency. Ablation
studies further confirm the effectiveness of PAFT.
