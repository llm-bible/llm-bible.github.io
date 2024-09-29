---
layout: publication
title: Fast and Effective Weight Update for Pruned Large Language Models
authors: Boža Vladimír
conference: "Arxiv"
year: 2024
bibkey: boža2024fast
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.02938"}
  - {name: "Code", url: "https://github.com/fmfi-compbio/admm-pruning"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'Pruning', 'Training Techniques']
---
Pruning large language models (LLMs) is a challenging task due to their enormous size. The primary difficulty is fine-tuning the model after pruning which is needed to recover the lost performance caused by dropping weights. Recent approaches have either ignored fine-tuning entirely focusing on efficient pruning criteria or attempted layer-wise weight updates preserving the behavior of each layer. However even layer-wise weight updates can be costly for LLMs and previous works have resorted to various approximations. In our paper we propose a fast and effective weight update algorithm for pruned layers based on the Alternating Direction Method of Multipliers (ADMM). We further extend it with a simple gradual pruning mask selection and achieve state-of-the-art pruning performance across a wide range of LLMs. Code is available at https://github.com/fmfi-compbio/admm-pruning.
