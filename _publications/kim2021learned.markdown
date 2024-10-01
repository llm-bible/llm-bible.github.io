---
layout: publication
title: 'Learned Token Pruning For Transformers'
authors: Kim Sehoon, Shen Sheng, Thorsley David, Gholami Amir, Kwon Woosuk, Hassoun Joseph, Keutzer Kurt
conference: "Arxiv"
year: 2021
bibkey: kim2021learned
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2107.00910"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Training Techniques', 'Transformer']
---
"Deploying transformer models in practice is challenging due to their inference cost, which scales quadratically with input sequence length. To address this, we present a novel Learned Token Pruning (LTP) method which adaptively removes unimportant tokens as an input sequence passes through transformer layers. In particular, LTP prunes tokens with an attention score below a threshold value which is learned for each layer during training. Our threshold-based method allows the length of the pruned sequence to vary adaptively based on the input sequence, and avoids algorithmically expensive operations such as top-k token selection. We extensively test the performance of LTP on GLUE tasks and show that our method outperforms the prior state-of-the-art token pruning methods by up to ~2.5&#37; higher accuracy with the same amount of FLOPs. In particular, LTP achieves up to 2.1x FLOPs reduction with less than 1&#37; accuracy drop, which results in up to 1.9x and 2.0x throughput improvement on Intel Haswell CPUs and NVIDIA V100 GPUs, respectively. Furthermore, we demonstrate that LTP is more robust than prior methods to variations on input sentence lengths. Our code has been developed in PyTorch and has been open-sourced."
