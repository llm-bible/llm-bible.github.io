---
layout: publication
title: Dial45;mae Contextual Masked Auto45;encoder For Retrieval45;based Dialogue Systems
authors: Su Zhenpeng, Wu Xing, Zhou Wei, Ma Guangyuan, Hu Songlin
conference: "Arxiv"
year: 2023
bibkey: su2023dial
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.04357"}
tags: ['Applications', 'BERT', 'Model Architecture', 'Training Techniques']
---
Dialogue response selection aims to select an appropriate response from several candidates based on a given user and system utterance history. Most existing works primarily focus on post45;training and fine45;tuning tailored for cross45;encoders. However there are no post45;training methods tailored for dense encoders in dialogue response selection. We argue that when the current language model based on dense dialogue systems (such as BERT) is employed as a dense encoder it separately encodes dialogue context and response leading to a struggle to achieve the alignment of both representations. Thus we propose Dial45;MAE (Dialogue Contextual Masking Auto45;Encoder) a straightforward yet effective post45;training technique tailored for dense encoders in dialogue response selection. Dial45;MAE uses an asymmetric encoder45;decoder architecture to compress the dialogue semantics into dense vectors which achieves better alignment between the features of the dialogue context and response. Our experiments have demonstrated that Dial45;MAE is highly effective achieving state45;of45;the45;art performance on two commonly evaluated benchmarks.
