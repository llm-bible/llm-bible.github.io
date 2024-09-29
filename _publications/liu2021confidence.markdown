---
layout: publication
title: Confidence45;aware Scheduled Sampling For Neural Machine Translation
authors: Liu Yijin, Meng Fandong, Chen Yufeng, Xu Jinan, Zhou Jie
conference: "Arxiv"
year: 2021
bibkey: liu2021confidence
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2107.10427"}
tags: ['Applications', 'Ethics And Bias', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Scheduled sampling is an effective method to alleviate the exposure bias problem of neural machine translation. It simulates the inference scene by randomly replacing ground45;truth target input tokens with predicted ones during training. Despite its success its critical schedule strategies are merely based on training steps ignoring the real45;time model competence which limits its potential performance and convergence speed. To address this issue we propose confidence45;aware scheduled sampling. Specifically we quantify real45;time model competence by the confidence of model predictions based on which we design fine45;grained schedule strategies. In this way the model is exactly exposed to predicted tokens for high45;confidence positions and still ground45;truth tokens for low45;confidence positions. Moreover we observe vanilla scheduled sampling suffers from degenerating into the original teacher forcing mode since most predicted tokens are the same as ground45;truth tokens. Therefore under the above confidence45;aware strategy we further expose more noisy tokens (e.g. wordy and incorrect word order) instead of predicted ones for high45;confidence token positions. We evaluate our approach on the Transformer and conduct experiments on large45;scale WMT 2014 English45;German WMT 2014 English45;French and WMT 2019 Chinese45;English. Results show that our approach significantly outperforms the Transformer and vanilla scheduled sampling on both translation quality and convergence speed.
