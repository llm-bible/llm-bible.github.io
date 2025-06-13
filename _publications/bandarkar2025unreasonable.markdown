---
layout: publication
title: 'The Unreasonable Effectiveness Of Model Merging For Cross-lingual Transfer In Llms'
authors: Lucas Bandarkar, Nanyun Peng
conference: "Arxiv"
year: 2025
bibkey: bandarkar2025unreasonable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18356"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'Merging', 'Pretraining Methods', 'Fine-Tuning', 'Interpretability and Explainability']
---
Large language models (LLMs) still struggle across tasks outside of high-resource languages. In this work, we investigate cross-lingual transfer to lower-resource languages where task-specific post-training data is scarce. Building on prior work, we first validate that the subsets of model parameters that matter most for mathematical reasoning and multilingual capabilities are distinctly non-overlapping. To exploit this implicit separability between task and target language parameterization, we develop and analyze numerous modular frameworks to improve the composition of the two during fine-tuning. These methods generally employ freezing parameters or post hoc model merging to assign math and language improvement to different key parts of the LLM. In the absence of in-language math data, we demonstrate that the modular approaches successfully improve upon baselines across three languages, four models, and two fine-tuning paradigms (full and LoRA). Furthermore, we identify the most consistently successful modular method to be fine-tuning separate language and math experts and model merging via Layer-Swapping, somewhat surprisingly. We offer possible explanations for this result via recent works on the linearity of task vectors. We further explain this by empirically showing that reverting less useful fine-tuning updates after training often outperforms freezing them from the start.
