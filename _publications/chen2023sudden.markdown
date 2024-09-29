---
layout: publication
title: Sudden Drops In The Loss\: Syntax Acquisition, Phase Transitions, And Simplicity Bias In Mlms
authors: Chen Angelica, Shwartz-ziv Ravid, Cho Kyunghyun, Leavitt Matthew L., Saphra Naomi
conference: "Arxiv"
year: 2023
bibkey: chen2023sudden
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.07311"}
tags: ['Attention Mechanism', 'BERT', 'Ethics And Bias', 'Interpretability And Explainability', 'Masked Language Model', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Most interpretability research in NLP focuses on understanding the behavior and features of a fully trained model. However certain insights into model behavior may only be accessible by observing the trajectory of the training process. We present a case study of syntax acquisition in masked language models (MLMs) that demonstrates how analyzing the evolution of interpretable artifacts throughout training deepens our understanding of emergent behavior. In particular we study Syntactic Attention Structure (SAS) a naturally emerging property of MLMs wherein specific Transformer heads tend to focus on specific syntactic relations. We identify a brief window in pretraining when models abruptly acquire SAS concurrent with a steep drop in loss. This breakthrough precipitates the subsequent acquisition of linguistic capabilities. We then examine the causal role of SAS by manipulating SAS during training and demonstrate that SAS is necessary for the development of grammatical capabilities. We further find that SAS competes with other beneficial traits during training and that briefly suppressing SAS improves model quality. These findings offer an interpretation of a real-world example of both simplicity bias and breakthrough training dynamics.
