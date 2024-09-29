---
layout: publication
title: Neural Machine Translation With Key45;value Memory45;augmented Attention
authors: Meng Fandong, Tu Zhaopeng, Cheng Yong, Wu Haiyang, Zhai Junjie, Yang Yuekui, Wang Di
conference: "Arxiv"
year: 2018
bibkey: meng2018neural
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1806.11249"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture']
---
Although attention45;based Neural Machine Translation (NMT) has achieved remarkable progress in recent years it still suffers from issues of repeating and dropping translations. To alleviate these issues we propose a novel key45;value memory45;augmented attention model for NMT called KVMEMATT. Specifically we maintain a timely updated keymemory to keep track of attention history and a fixed value45;memory to store the representation of source sentence throughout the whole translation process. Via nontrivial transformations and iterative interactions between the two memories the decoder focuses on more appropriate source word(s) for predicting the next target word at each decoding step therefore can improve the adequacy of translations. Experimental results on Chinese=English and WMT17 German<=English translation tasks demonstrate the superiority of the proposed model.
