---
layout: publication
title: 'LIV: Language-image Representations And Rewards For Robotic Control'
authors: Yecheng Jason Ma et al.
conference: Arxiv
year: 2023
citations: 16
bibkey: ma2023language
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.00958'}]
tags: [Multimodal Models, Reinforcement Learning]
---
We present Language-Image Value learning (LIV), a unified objective for
vision-language representation and reward learning from action-free videos with
text annotations. Exploiting a novel connection between dual reinforcement
learning and mutual information contrastive learning, the LIV objective trains
a multi-modal representation that implicitly encodes a universal value function
for tasks specified as language or image goals. We use LIV to pre-train the
first control-centric vision-language representation from large human video
datasets such as EpicKitchen. Given only a language or image goal, the
pre-trained LIV model can assign dense rewards to each frame in videos of
unseen robots or humans attempting that task in unseen environments. Further,
when some target domain-specific data is available, the same objective can be
used to fine-tune and improve LIV and even other pre-trained representations
for robotic control and reward specification in that domain. In our experiments
on several simulated and real-world robot environments, LIV models consistently
outperform the best prior input state representations for imitation learning,
as well as reward specification methods for policy synthesis. Our results
validate the advantages of joint vision-language representation and reward
learning within the unified, compact LIV framework.