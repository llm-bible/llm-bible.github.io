---
layout: publication
title: 'Prefix Propagation: Parameter-efficient Tuning For Long Sequences'
authors: Li Jonathan, Aitken Will, Bhambhoria Rohan, Zhu Xiaodan
conference: "Arxiv"
year: 2023
bibkey: li2023prefix
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.12086"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Parameter-efficient tuning aims to mitigate the large memory requirements of adapting pretrained language models for downstream tasks. For example one popular method prefix-tuning prepends trainable tokens to sequences while freezing the rest of the models parameters. Although such models attain comparable performance with fine-tuning when applied to sequences with short to moderate lengths we show their inferior performance when modelling long sequences. To bridge this gap we propose prefix-propagation a simple but effective approach that conditions prefixes on previous hidden states. We empirically demonstrate that prefix-propagation outperforms prefix-tuning across long-document tasks while using 5037; fewer parameters. To further investigate the proposed architecture we also show its advantage in calibration and perform additional study on its relationship with kernel attention. To the best of our knowledge this work is the first to focus on parameter-efficient learning for long-sequence language tasks.
