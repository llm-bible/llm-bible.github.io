---
layout: publication
title: Random45;ltd Random And Layerwise Token Dropping Brings Efficient Training For Large45;scale Transformers
authors: Yao Zhewei, Wu Xiaoxia, Li Conglong, Holmes Connor, Zhang Minjia, Li Cheng, He Yuxiong
conference: "Arxiv"
year: 2022
bibkey: yao2022random
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.11586"}
tags: ['Applications', 'BERT', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Large45;scale transformer models have become the de45;facto architectures for various machine learning applications e.g. CV and NLP. However those large models also introduce prohibitive training costs. To mitigate this issue we propose a novel random and layerwise token dropping method (random45;LTD) which skips the computation of a subset of the input tokens at all middle layers. Particularly random45;LTD achieves considerable speedups and comparable accuracy as the standard training baseline. Compared to other token dropping methods random45;LTD does not require (1) any importance score45;based metrics (2) any special token treatment (e.g. CLS) and (3) many layers in full sequence length training except the first and the last layers. Besides a new LayerToken learning rate schedule is proposed for pretraining problems that resolve the heavy tuning requirement for our proposed training mechanism. Finally we demonstrate that random45;LTD can be applied to broader applications including GPT and BERT pretraining as well as ViT and GPT finetuning tasks. Our results show that random45;LTD can save about 33.337; theoretical compute cost and 25.637; wall45;clock training time while achieving similar zero45;shot evaluations on GPT45;31.3B as compared to baseline.
