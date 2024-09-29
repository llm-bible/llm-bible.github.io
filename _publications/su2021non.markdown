---
layout: publication
title: 'Non-autoregressive Text Generation With Pre-trained Language Models'
authors: Su Yixuan, Cai Deng, Wang Yan, Vandyke David, Baker Simon, Li Piji, Collier Nigel
conference: "Arxiv"
year: 2021
bibkey: su2021non
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2102.08220"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods']
---
Non-autoregressive generation (NAG) has recently attracted great attention due to its fast inference speed. However the generation quality of existing NAG models still lags behind their autoregressive counterparts. In this work we show that BERT can be employed as the backbone of a NAG model to greatly improve performance. Additionally we devise mechanisms to alleviate the two common problems of vanilla NAG models the inflexibility of prefixed output length and the conditional independence of individual token predictions. Lastly to further increase the speed advantage of the proposed model we propose a new decoding strategy ratio-first for applications where the output lengths can be approximately estimated beforehand. For a comprehensive evaluation we test the proposed model on three text generation tasks including text summarization sentence compression and machine translation. Experimental results show that our model significantly outperforms existing non-autoregressive baselines and achieves competitive performance with many strong autoregressive models. In addition we also conduct extensive analysis experiments to reveal the effect of each proposed component.
