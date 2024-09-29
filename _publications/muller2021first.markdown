---
layout: publication
title: First Align, Then Predict\: Understanding The Cross-lingual Ability Of Multilingual BERT
authors: Muller Benjamin, Elazar Yanai, Sagot Benoît, Seddah Djamé
conference: "Arxiv"
year: 2021
bibkey: muller2021first
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2101.11109"}
tags: ['BERT', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Multilingual pretrained language models have demonstrated remarkable zero-shot cross-lingual transfer capabilities. Such transfer emerges by fine-tuning on a task of interest in one language and evaluating on a distinct language not seen during the fine-tuning. Despite promising results we still lack a proper understanding of the source of this transfer. Using a novel layer ablation technique and analyses of the models internal representations we show that multilingual BERT a popular multilingual language model can be viewed as the stacking of two sub-networks a multilingual encoder followed by a task-specific language-agnostic predictor. While the encoder is crucial for cross-lingual transfer and remains mostly unchanged during fine-tuning the task predictor has little importance on the transfer and can be reinitialized during fine-tuning. We present extensive experiments with three distinct tasks seventeen typologically diverse languages and multiple domains to support our hypothesis.
