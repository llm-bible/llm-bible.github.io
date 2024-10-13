---
layout: publication
title: 'Prompt Your Brain: Scaffold Prompt Tuning For Efficient Adaptation Of Fmri Pre-trained Model'
authors: Dong Zijian, Wu Yilei, Chen Zijiao, Zhang Yichi, Jin Yueming, Zhou Juan Helen
conference: "Arxiv"
year: 2024
bibkey: dong2024prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10567"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques', 'Transformer']
---
We introduce Scaffold Prompt Tuning (ScaPT), a novel prompt-based framework
for adapting large-scale functional magnetic resonance imaging (fMRI)
pre-trained models to downstream tasks, with high parameter efficiency and
improved performance compared to fine-tuning and baselines for prompt tuning.
The full fine-tuning updates all pre-trained parameters, which may distort the
learned feature space and lead to overfitting with limited training data which
is common in fMRI fields. In contrast, we design a hierarchical prompt
structure that transfers the knowledge learned from high-resource tasks to
low-resource ones. This structure, equipped with a Deeply-conditioned
Input-Prompt (DIP) mapping module, allows for efficient adaptation by updating
only 2% of the trainable parameters. The framework enhances semantic
interpretability through attention mechanisms between inputs and prompts, and
it clusters prompts in the latent space in alignment with prior knowledge.
Experiments on public resting state fMRI datasets reveal ScaPT outperforms
fine-tuning and multitask-based prompt tuning in neurodegenerative diseases
diagnosis/prognosis and personality trait prediction, even with fewer than 20
participants. It highlights ScaPT's efficiency in adapting pre-trained fMRI
models to low-resource tasks.
