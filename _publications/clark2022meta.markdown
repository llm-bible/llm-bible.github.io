---
layout: publication
title: Meta-Learning Fast Weight Language Models
authors: Clark Kevin, Guu Kelvin, Chang Ming-wei, Pasupat Panupong, Hinton Geoffrey, Norouzi Mohammad
conference: "Arxiv"
year: 2022
bibkey: clark2022meta
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.02475"}
tags: ['Attention Mechanism', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Dynamic evaluation of language models (LMs) adapts model parameters at test time using gradient information from previous tokens and substantially improves LM performance. However it requires over 3x more compute than standard inference. We present Fast Weight Layers (FWLs) a neural component that provides the benefits of dynamic evaluation much more efficiently by expressing gradient updates as linear attention. A key improvement over dynamic evaluation is that FWLs can also be applied at training time so the model learns to make good use of gradient updates. FWLs can easily be added on top of existing transformer models require relatively little extra compute or memory to run and significantly improve language modeling perplexity.
