---
layout: publication
title: 'Intent-enhanced Data Augmentation For Sequential Recommendation'
authors: Shuai Chen, Zhoujun Li
conference: "Arxiv"
year: 2024
bibkey: chen2024intent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.08583"}
tags: ['Training Techniques', 'Reinforcement Learning', 'RAG', 'RecSys', 'Pretraining Methods']
---
The research on intent-enhanced sequential recommendation algorithms focuses
on how to better mine dynamic user intent based on user behavior data for
sequential recommendation tasks. Various data augmentation methods are widely
applied in current sequential recommendation algorithms, effectively enhancing
the ability to capture user intent. However, these widely used data
augmentation methods often rely on a large amount of random sampling, which can
introduce excessive noise into the training data, blur user intent, and thus
negatively affect recommendation performance. Additionally, these methods have
limited approaches to utilizing augmented data, failing to fully leverage the
augmented samples. We propose an intent-enhanced data augmentation method for
sequential recommendation(\textbf\{IESRec\}), which constructs positive and
negative samples based on user behavior sequences through intent-segment
insertion. On one hand, the generated positive samples are mixed with the
original training data, and they are trained together to improve recommendation
performance. On the other hand, the generated positive and negative samples are
used to build a contrastive loss function, enhancing recommendation performance
through self-supervised training. Finally, the main recommendation task is
jointly trained with the contrastive learning loss minimization task.
Experiments on three real-world datasets validate the effectiveness of our
IESRec model.
