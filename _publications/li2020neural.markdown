---
layout: publication
title: Neural Machine Translation With Joint Representation
authors: Li Yanyang, Wang Qiang, Xiao Tong, Liu Tongran, Zhu Jingbo
conference: "Arxiv"
year: 2020
bibkey: li2020neural
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2002.06546"}
  - {name: "Code", url: "https://github.com/lyy1994/reformer"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Scaling Laws', 'Tools', 'Transformer']
---
Though early successes of Statistical Machine Translation (SMT) systems are attributed in part to the explicit modelling of the interaction between any two source and target units e.g. alignment the recent Neural Machine Translation (NMT) systems resort to the attention which partially encodes the interaction for efficiency. In this paper we employ Joint Representation that fully accounts for each possible interaction. We sidestep the inefficiency issue by refining representations with the proposed efficient attention operation. The resulting Reformer models offer a new Sequence45;to45; Sequence modelling paradigm besides the Encoder45;Decoder framework and outperform the Transformer baseline in either the small scale IWSLT14 German45;English English45;German and IWSLT15 Vietnamese45;English or the large scale NIST12 Chinese45;English translation tasks by about 1 BLEU point.We also propose a systematic model scaling approach allowing the Reformer model to beat the state45;of45;the45;art Transformer in IWSLT14 German45;English and NIST12 Chinese45;English with about 5037; fewer parameters. The code is publicly available at https://github.com/lyy1994/reformer.
