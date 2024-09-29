---
layout: publication
title: Random-ltd&#58; Random And Layerwise Token Dropping Brings Efficient Training For Large-scale Transformers
authors: Yao Zhewei, Wu Xiaoxia, Li Conglong, Holmes Connor, Zhang Minjia, Li Cheng, He Yuxiong
conference: "Arxiv"
year: 2022
bibkey: yao2022random
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.11586"}
tags: ['Applications', 'BERT', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Large-scale transformer models have become the de-facto architectures for various machine learning applications e.g. CV and NLP. However those large models also introduce prohibitive training costs. To mitigate this issue we propose a novel random and layerwise token dropping method (random-LTD) which skips the computation of a subset of the input tokens at all middle layers. Particularly random-LTD achieves considerable speedups and comparable accuracy as the standard training baseline. Compared to other token dropping methods random-LTD does not require (1) any importance score-based metrics (2) any special token treatment (e.g. CLS) and (3) many layers in full sequence length training except the first and the last layers. Besides a new LayerToken learning rate schedule is proposed for pretraining problems that resolve the heavy tuning requirement for our proposed training mechanism. Finally we demonstrate that random-LTD can be applied to broader applications including GPT and BERT pretraining as well as ViT and GPT finetuning tasks. Our results show that random-LTD can save about 33.337; theoretical compute cost and 25.637; wall-clock training time while achieving similar zero-shot evaluations on GPT-31.3B as compared to baseline.
