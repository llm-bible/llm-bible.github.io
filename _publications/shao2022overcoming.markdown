---
layout: publication
title: 'Overcoming Catastrophic Forgetting Beyond Continual Learning: Balanced Training For Neural Machine Translation'
authors: Chenze Shao, Yang Feng
conference: "Arxiv"
year: 2022
bibkey: shao2022overcoming
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.03910"}
tags: ['Efficiency and Optimization', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Distillation']
---
Neural networks tend to gradually forget the previously learned knowledge
when learning multiple tasks sequentially from dynamic data distributions. This
problem is called \textit\{catastrophic forgetting\}, which is a fundamental
challenge in the continual learning of neural networks. In this work, we
observe that catastrophic forgetting not only occurs in continual learning but
also affects the traditional static training. Neural networks, especially
neural machine translation models, suffer from catastrophic forgetting even if
they learn from a static training set. To be specific, the final model pays
imbalanced attention to training samples, where recently exposed samples
attract more attention than earlier samples. The underlying cause is that
training samples do not get balanced training in each model update, so we name
this problem \textit\{imbalanced training\}. To alleviate this problem, we
propose Complementary Online Knowledge Distillation (COKD), which uses
dynamically updated teacher models trained on specific data orders to
iteratively provide complementary knowledge to the student model. Experimental
results on multiple machine translation tasks show that our method successfully
alleviates the problem of imbalanced training and achieves substantial
improvements over strong baseline systems.
