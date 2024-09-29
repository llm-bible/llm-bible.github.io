---
layout: publication
title: Weighted Transformer Network For Machine Translation
authors: Ahmed Karim, Keskar Nitish Shirish, Socher Richard
conference: "Arxiv"
year: 2017
bibkey: ahmed2017weighted
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1711.02132"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
State45;of45;the45;art results on neural machine translation often use attentional sequence45;to45;sequence models with some form of convolution or recursion. Vaswani et al. (2017) propose a new architecture that avoids recurrence and convolution completely. Instead it uses only self45;attention and feed45;forward layers. While the proposed architecture achieves state45;of45;the45;art results on several machine translation tasks it requires a large number of parameters and training iterations to converge. We propose Weighted Transformer a Transformer with modified attention layers that not only outperforms the baseline network in BLEU score but also converges 1545;4037; faster. Specifically we replace the multi45;head attention by multiple self45;attention branches that the model learns to combine during the training process. Our model improves the state45;of45;the45;art performance by 0.5 BLEU points on the WMT 2014 English45;to45;German translation task and by 0.4 on the English45;to45;French translation task.
