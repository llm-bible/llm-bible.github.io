---
layout: publication
title: Binary And Ternary Natural Language Generation
authors: Liu Zechun, Oguz Barlas, Pappu Aasish, Shi Yangyang, Krishnamoorthi Raghuraman
conference: "Arxiv"
year: 2023
bibkey: liu2023binary
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.01841"}
  - {name: "Code", url: "https://github.com/facebookresearch/Ternary&#95;Binary&#95;Transformer"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'GPT', 'Has Code', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'Transformer']
---
Ternary and binary neural networks enable multiplication45;free computation and promise multiple orders of magnitude efficiency gains over full45;precision networks if implemented on specialized hardware. However since both the parameter and the output space are highly discretized such networks have proven very difficult to optimize. The difficulties are compounded for the class of transformer text generation models due to the sensitivity of the attention operation to quantization and the noise45;compounding effects of autoregressive decoding in the high45;cardinality output space. We approach the problem with a mix of statistics45;based quantization for the weights and elastic quantization of the activations and demonstrate the first ternary and binary transformer models on the downstream tasks of summarization and machine translation. Our ternary BART base achieves an R1 score of 41 on the CNN/DailyMail benchmark which is merely 3.9 points behind the full model while being 16x more efficient. Our binary model while less accurate achieves a highly non45;trivial score of 35.6. For machine translation we achieved BLEU scores of 21.7 and 17.6 on the WMT16 En45;Ro benchmark compared with a full precision mBART model score of 26.8. We also compare our approach in the 845;bit activation setting where our ternary and even binary weight models can match or outperform the best existing 845;bit weight models in the literature. Our code and models are available at https://github.com/facebookresearch/Ternary&#95;Binary&#95;Transformer
