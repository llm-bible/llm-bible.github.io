---
layout: publication
title: 'Interpretable Visual Question Answering Via Reasoning Supervision'
authors: Maria Parelli, Dimitrios Mallis, Markos Diomataris, Vassilis Pitsikalis
conference: "Arxiv"
year: 2023
bibkey: parelli2023interpretable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.03726'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'Training Techniques', 'Model Architecture', 'Applications', 'Multimodal Models', 'Ethics and Bias', 'Pretraining Methods']
---
Transformer-based architectures have recently demonstrated remarkable
performance in the Visual Question Answering (VQA) task. However, such models
are likely to disregard crucial visual cues and often rely on multimodal
shortcuts and inherent biases of the language modality to predict the correct
answer, a phenomenon commonly referred to as lack of visual grounding. In this
work, we alleviate this shortcoming through a novel architecture for visual
question answering that leverages common sense reasoning as a supervisory
signal. Reasoning supervision takes the form of a textual justification of the
correct answer, with such annotations being already available on large-scale
Visual Common Sense Reasoning (VCR) datasets. The model's visual attention is
guided toward important elements of the scene through a similarity loss that
aligns the learned attention distributions guided by the question and the
correct reasoning. We demonstrate both quantitatively and qualitatively that
the proposed approach can boost the model's visual perception capability and
lead to performance increase, without requiring training on explicit grounding
annotations.
