---
layout: publication
title: 'Think Or Step-by-step? Unzipping The Black Box In Zero-shot Prompts'
authors: Nikta Gohari Sadr, Sangmitra Madhusudan, Ali Emami
conference: "Arxiv"
year: 2025
bibkey: sadr2025think
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.03418"}
tags: ['Interpretability and Explainability', 'Attention Mechanism', 'Prompting', 'Model Architecture']
---
Zero-shot prompting techniques have significantly improved the performance of
Large Language Models (LLMs). However, we lack a clear understanding of why
zero-shot prompts are so effective. For example, in the prompt "Let's think
step-by-step," is "think" or "step-by-step" more crucial to its success?
Existing interpretability methods, such as gradient-based and attention-based
approaches, are computationally intensive and restricted to open-source models.
We introduce the ZIP score (Zero-shot Importance of Perturbation score), a
versatile metric applicable to both open and closed-source models, based on
systematic input word perturbations. Our experiments across four recent LLMs,
seven widely-used prompts, and several tasks, reveal interesting patterns in
word importance. For instance, while both 'step-by-step' and 'think' show high
ZIP scores, which one is more influential depends on the model and task. We
validate our method using controlled experiments and compare our results with
human judgments, finding that proprietary models align more closely with human
intuition regarding word significance. These findings enhance our understanding
of LLM behavior and contribute to developing more effective zero-shot prompts
and improved model analysis.
