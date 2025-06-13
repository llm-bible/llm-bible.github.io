---
layout: publication
title: 'Grounding Dialogue Systems Via Knowledge Graph Aware Decoding With Pre-trained Transformers'
authors: Debanjan Chaudhuri, Md Rashad Al Hasan Rony, Jens Lehmann
conference: "Arxiv"
year: 2021
bibkey: chaudhuri2021grounding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2103.16289'}
tags: ['Transformer', 'Training Techniques', 'BERT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Generating knowledge grounded responses in both goal and non-goal oriented
dialogue systems is an important research challenge. Knowledge Graphs (KG) can
be viewed as an abstraction of the real world, which can potentially facilitate
a dialogue system to produce knowledge grounded responses. However, integrating
KGs into the dialogue generation process in an end-to-end manner is a
non-trivial task. This paper proposes a novel architecture for integrating KGs
into the response generation process by training a BERT model that learns to
answer using the elements of the KG (entities and relations) in a multi-task,
end-to-end setting. The k-hop subgraph of the KG is incorporated into the model
during training and inference using Graph Laplacian. Empirical evaluation
suggests that the model achieves better knowledge groundedness (measured via
Entity F1 score) compared to other state-of-the-art models for both goal and
non-goal oriented dialogues.
