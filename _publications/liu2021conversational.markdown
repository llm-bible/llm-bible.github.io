---
layout: publication
title: 'Conversational Query Rewriting With Self-supervised Learning'
authors: Hang Liu, Meng Chen, Youzheng Wu, Xiaodong He, Bowen Zhou
conference: "Arxiv"
year: 2021
bibkey: liu2021conversational
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2102.04708"}
tags: ['Pretraining Methods', 'Training Techniques', 'Transformer', 'Model Architecture']
---
Context modeling plays a critical role in building multi-turn dialogue
systems. Conversational Query Rewriting (CQR) aims to simplify the multi-turn
dialogue modeling into a single-turn problem by explicitly rewriting the
conversational query into a self-contained utterance. However, existing
approaches rely on massive supervised training data, which is labor-intensive
to annotate. And the detection of the omitted important information from
context can be further improved. Besides, intent consistency constraint between
contextual query and rewritten query is also ignored. To tackle these issues,
we first propose to construct a large-scale CQR dataset automatically via
self-supervised learning, which does not need human annotation. Then we
introduce a novel CQR model Teresa based on Transformer, which is enhanced by
self-attentive keywords detection and intent consistency constraint. Finally,
we conduct extensive experiments on two public datasets. Experimental results
demonstrate that our proposed model outperforms existing CQR baselines
significantly, and also prove the effectiveness of self-supervised learning on
improving the CQR performance.
