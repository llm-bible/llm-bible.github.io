---
layout: publication
title: Efficient Long Sequence Modeling via State Space Augmented Transformer
authors: Zuo Simiao, Liu Xiaodong, Jiao Jian, Charles Denis, Manavoglu Eren, Zhao Tuo, Gao Jianfeng
conference: "Arxiv"
year: 2022
bibkey: zuo2022efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.08136"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Transformer models have achieved superior performance in various natural language processing tasks. However the quadratic computational cost of the attention mechanism limits its practicality for long sequences. There are existing attention variants that improve the computational efficiency but they have limited ability to effectively compute global information. In parallel to Transformer models state space models (SSMs) are tailored for long sequences but they are not flexible enough to capture complicated local information. We propose SPADE short for tate sace ugmente Transformr. Specifically we augment a SSM into the bottom layer of SPADE and we employ efficient local attention methods for the other layers. The SSM augments global information which complements the lack of long-range dependency issue in local attention methods. Experimental results on the Long Range Arena benchmark and language modeling tasks demonstrate the effectiveness of the proposed method. To further demonstrate the scalability of SPADE we pre-train large encoder-decoder models and present fine-tuning results on natural language understanding and natural language generation tasks.
