---
layout: publication
title: 'Local And Global Contexts For Conversation'
authors: Lin Zuoquan, Shen Xinyi
conference: "Arxiv"
year: 2024
bibkey: lin2024local
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.17588"}
tags: ['Merging', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
The context in conversation is the dialog history crucial for multi-turn dialogue. Learning from the relevant contexts in dialog history for grounded conversation is a challenging problem. Local context is the most neighbor and more sensitive to the subsequent response, and global context is relevant to a whole conversation far beyond neighboring utterances. Currently, pretrained transformer models for conversation challenge capturing the correlation and connection between local and global contexts. We introduce a local and global conversation model (LGCM) for general-purpose conversation in open domain. It is a local-global hierarchical transformer model that excels at accurately discerning and assimilating the relevant contexts necessary for generating responses. It employs a local encoder to grasp the local context at the level of individual utterances and a global encoder to understand the broader context at the dialogue level. The seamless fusion of these locally and globally contextualized encodings ensures a comprehensive comprehension of the conversation. Experiments on popular datasets show that LGCM outperforms the existing conversation models on the performance of automatic metrics with significant margins.
