---
layout: publication
title: "Generating Coherent Narratives By Learning Dynamic And Discrete Entity States With A Contrastive Framework"
authors: Guan Jian, Yang Zhenyu, Zhang Rongsheng, Hu Zhipeng, Huang Minlie
conference: "Arxiv"
year: 2022
bibkey: guan2022generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.03985"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Despite advances in generating fluent texts existing pretraining models tend to attach incoherent event sequences to involved entities when generating narratives such as stories and news. We conjecture that such issues result from representing entities as static embeddings of superficial words while neglecting to model their ever-changing states i.e. the information they carry as the text unfolds. Therefore we extend the Transformer model to dynamically conduct entity state updates and sentence realization for narrative generation. We propose a contrastive framework to learn the state representations in a discrete space and insert additional attention layers into the decoder to better exploit these states. Experiments on two narrative datasets show that our model can generate more coherent and diverse narratives than strong baselines with the guidance of meaningful entity states.
