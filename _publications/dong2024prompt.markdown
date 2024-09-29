---
layout: publication
title: Prompt Your Brain Scaffold Prompt Tuning For Efficient Adaptation Of Fmri Pre45;trained Model
authors: Dong Zijian, Wu Yilei, Chen Zijiao, Zhang Yichi, Jin Yueming, Zhou Juan Helen
conference: "Arxiv"
year: 2024
bibkey: dong2024prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10567"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Interpretability And Explainability', 'Model Architecture', 'Prompting', 'Tools', 'Training Techniques', 'Transformer']
---
We introduce Scaffold Prompt Tuning (ScaPT) a novel prompt45;based framework for adapting large45;scale functional magnetic resonance imaging (fMRI) pre45;trained models to downstream tasks with high parameter efficiency and improved performance compared to fine45;tuning and baselines for prompt tuning. The full fine45;tuning updates all pre45;trained parameters which may distort the learned feature space and lead to overfitting with limited training data which is common in fMRI fields. In contrast we design a hierarchical prompt structure that transfers the knowledge learned from high45;resource tasks to low45;resource ones. This structure equipped with a Deeply45;conditioned Input45;Prompt (DIP) mapping module allows for efficient adaptation by updating only 237; of the trainable parameters. The framework enhances semantic interpretability through attention mechanisms between inputs and prompts and it clusters prompts in the latent space in alignment with prior knowledge. Experiments on public resting state fMRI datasets reveal ScaPT outperforms fine45;tuning and multitask45;based prompt tuning in neurodegenerative diseases diagnosis/prognosis and personality trait prediction even with fewer than 20 participants. It highlights ScaPTs efficiency in adapting pre45;trained fMRI models to low45;resource tasks.
