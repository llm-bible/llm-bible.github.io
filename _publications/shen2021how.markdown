---
layout: publication
title: How Much Can CLIP Benefit Vision45;and45;language Tasks
authors: Shen Sheng, Li Liunian Harold, Tan Hao, Bansal Mohit, Rohrbach Anna, Chang Kai-wei, Yao Zhewei, Keutzer Kurt
conference: "Arxiv"
year: 2021
bibkey: shen2021how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2107.06383"}
  - {name: "Code", url: "https://github.com/clip&#45;vil/CLIP&#45;ViL"}
tags: ['Applications', 'Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Most existing Vision45;and45;Language (Vamp;L) models rely on pre45;trained visual encoders using a relatively small set of manually45;annotated data (as compared to web45;crawled data) to perceive the visual world. However it has been observed that large45;scale pretraining usually can result in better generalization performance e.g. CLIP (Contrastive Language45;Image Pre45;training) trained on a massive amount of image45;caption pairs has shown a strong zero45;shot capability on various vision tasks. To further study the advantage brought by CLIP we propose to use CLIP as the visual encoder in various Vamp;L models in two typical scenarios 1) plugging CLIP into task45;specific fine45;tuning; 2) combining CLIP with Vamp;L pre45;training and transferring to downstream tasks. We show that CLIP significantly outperforms widely45;used visual encoders trained with in45;domain annotated data such as BottomUp45;TopDown. We achieve competitive or better results on diverse Vamp;L tasks while establishing new state45;of45;the45;art results on Visual Question Answering Visual Entailment and Vamp;L Navigation tasks. We release our code at https://github.com/clip&#45;vil/CLIP&#45;ViL.
