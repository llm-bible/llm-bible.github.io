---
layout: publication
title: Ctrlstruct Dialogue Structure Learning For Open45;domain Response Generation
authors: Yin Congchi, Li Piji, Ren Zhaochun
conference: "Arxiv"
year: 2023
bibkey: yin2023dialogue
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.01094"}
tags: ['Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Transformer']
---
Dialogue structure discovery is essential in dialogue generation. Well45;structured topic flow can leverage background information and predict future topics to help generate controllable and explainable responses. However most previous work focused on dialogue structure learning in task45;oriented dialogue other than open45;domain dialogue which is more complicated and challenging. In this paper we present a new framework CTRLStruct for dialogue structure learning to effectively explore topic45;level dialogue clusters as well as their transitions with unlabelled information. Precisely dialogue utterances encoded by bi45;directional Transformer are further trained through a special designed contrastive learning task to improve representation. Then we perform clustering to utterance45;level representations and form topic45;level clusters that can be considered as vertices in dialogue structure graph. The edges in the graph indicating transition probability between vertices are calculated by mimicking expert behavior in datasets. Finally dialogue structure graph is integrated into dialogue model to perform controlled response generation. Experiments on two popular open45;domain dialogue datasets show our model can generate more coherent responses compared to some excellent dialogue models as well as outperform some typical sentence embedding methods in dialogue utterance representation. Code is available in GitHub.
