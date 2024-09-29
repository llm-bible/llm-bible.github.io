---
layout: publication
title: Jump To Conclusions Short-cutting Transformers With Linear Transformations
authors: Din Alexander Yom, Karidi Taelin, Choshen Leshem, Geva Mor
conference: "LREC-COLING"
year: 2023
bibkey: din2023jump
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.09435"}
  - {name: "Code", url: "https://github.com/sashayd/mat"}
tags: ['Attention Mechanism', 'BERT', 'GPT', 'Has Code', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Transformer-based language models create hidden representations of their inputs at every layer but only use final-layer representations for prediction. This obscures the internal decision-making process of the model and the utility of its intermediate representations. One way to elucidate this is to cast the hidden representations as final representations bypassing the transformer computation in-between. In this work we suggest a simple method for such casting using linear transformations. This approximation far exceeds the prevailing practice of inspecting hidden representations from all layers in the space of the final layer. Moreover in the context of language modeling our method produces more accurate predictions from hidden layers across various model scales architectures and data distributions. This allows peeking into intermediate representations showing that GPT-2 and BERT often predict the final output already in early layers. We then demonstrate the practicality of our method to recent early exit strategies showing that when aiming for example at retention of 9537; accuracy our approach saves additional 7.937; layers for GPT-2 and 5.437; layers for BERT. Last we extend our method to linearly approximate sub-modules finding that attention is most tolerant to this change. Our code and learned mappings are publicly available at https://github.com/sashayd/mat."
