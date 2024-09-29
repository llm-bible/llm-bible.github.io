---
layout: publication
title: Improving Sequential Recommendation Consistency With Self45;supervised Imitation
authors: Yuan Xu, Chen Hongshen, Song Yonghao, Zhao Xiaofang, Ding Zhuoye, He Zhen, Long Bo
conference: "Arxiv"
year: 2021
bibkey: yuan2021improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.14031"}
tags: ['Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Most sequential recommendation models capture the features of consecutive items in a user45;item interaction history. Though effective their representation expressiveness is still hindered by the sparse learning signals. As a result the sequential recommender is prone to make inconsistent predictions. In this paper we propose a model SSI to improve sequential recommendation consistency with Self45;Supervised Imitation. Precisely we extract the consistency knowledge by utilizing three self45;supervised pre45;training tasks where temporal consistency and persona consistency capture user45;interaction dynamics in terms of the chronological order and persona sensitivities respectively. Furthermore to provide the model with a global perspective global session consistency is introduced by maximizing the mutual information among global and local interaction sequences. Finally to comprehensively take advantage of all three independent aspects of consistency45;enhanced knowledge we establish an integrated imitation learning framework. The consistency knowledge is effectively internalized and transferred to the student model by imitating the conventional prediction logit as well as the consistency45;enhanced item representations. In addition the flexible self45;supervised imitation framework can also benefit other student recommenders. Experiments on four real45;world datasets show that SSI effectively outperforms the state45;of45;the45;art sequential recommendation methods.
