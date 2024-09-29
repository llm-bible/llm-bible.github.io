---
layout: publication
title: Various Lengths Constant Speed Efficient Language Modeling With Lightning Attention
authors: Qin Zhen, Sun Weigao, Li Dong, Shen Xuyang, Sun Weixuan, Zhong Yiran
conference: "Arxiv"
year: 2024
bibkey: qin2024various
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17381"}
tags: ['Attention Mechanism', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
We present Lightning Attention the first linear attention implementation that maintains a constant training speed for various sequence lengths under fixed memory consumption. Due to the issue with cumulative summation operations (cumsum) previous linear attention implementations cannot achieve their theoretical advantage in a casual setting. However this issue can be effectively solved by utilizing different attention calculation strategies to compute the different parts of attention. Specifically we split the attention calculation into intra45;blocks and inter45;blocks and use conventional attention computation for intra45;blocks and linear attention kernel tricks for inter45;blocks. This eliminates the need for cumsum in the linear attention calculation. Furthermore a tiling technique is adopted through both forward and backward procedures to take full advantage of the GPU hardware. To enhance accuracy while preserving efficacy we introduce TransNormerLLM (TNL) a new architecture that is tailored to our lightning attention. We conduct rigorous testing on standard and self45;collected datasets with varying model sizes and sequence lengths. TNL is notably more efficient than other language models. In addition benchmark results indicate that TNL performs on par with state45;of45;the45;art LLMs utilizing conventional transformer structures. The source code is released at github.com/OpenNLPLab/TransnormerLLM.
