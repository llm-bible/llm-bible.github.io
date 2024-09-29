---
layout: publication
title: Hyena Hierarchy Towards Larger Convolutional Language Models
authors: Poli Michael, Massaroli Stefano, Nguyen Eric, Fu Daniel Y., Dao Tri, Baccus Stephen, Bengio Yoshua, Ermon Stefano, Ré Christopher
conference: "Arxiv"
year: 2023
bibkey: poli2023hyena
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.10866"}
tags: ['Attention Mechanism', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Recent advances in deep learning have relied heavily on the use of large Transformers due to their ability to learn at scale. However the core building block of Transformers the attention operator exhibits quadratic cost in sequence length limiting the amount of context accessible. Existing subquadratic methods based on low45;rank and sparse approximations need to be combined with dense attention layers to match Transformers indicating a gap in capability. In this work we propose Hyena a subquadratic drop45;in replacement for attention constructed by interleaving implicitly parametrized long convolutions and data45;controlled gating. In recall and reasoning tasks on sequences of thousands to hundreds of thousands of tokens Hyena improves accuracy by more than 50 points over operators relying on state45;spaces and other implicit and explicit methods matching attention45;based models. We set a new state45;of45;the45;art for dense45;attention45;free architectures on language modeling in standard datasets (WikiText103 and The Pile) reaching Transformer quality with a 2037; reduction in training compute required at sequence length 2K. Hyena operators are twice as fast as highly optimized attention at sequence length 8K and 100x faster at sequence length 64K.
