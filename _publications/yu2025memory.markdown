---
layout: publication
title: 'Memory Reviving, Continuing Learning And Beyond: Evaluation Of Pre-trained Encoders And Decoders For Multimodal Machine Translation'
authors: Zhuang Yu, Shiliang Sun, Jing Zhao, Tengfei Song, Hao Yang
conference: "Arxiv"
year: 2025
bibkey: yu2025memory
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.18012'}
tags: ['RAG', 'Model Architecture', 'Tools', 'Training Techniques', 'Merging', 'Applications', 'Multimodal Models', 'Pre-Training']
---
Multimodal Machine Translation (MMT) aims to improve translation quality by
leveraging auxiliary modalities such as images alongside textual input. While
recent advances in large-scale pre-trained language and vision models have
significantly benefited unimodal natural language processing tasks, their
effectiveness and role in MMT remain underexplored. In this work, we conduct a
systematic study on the impact of pre-trained encoders and decoders in
multimodal translation models. Specifically, we analyze how different training
strategies, from training from scratch to using pre-trained and partially
frozen components, affect translation performance under a unified MMT
framework. Experiments are carried out on the Multi30K and CoMMuTE dataset
across English-German and English-French translation tasks. Our results reveal
that pre-training plays a crucial yet asymmetrical role in multimodal settings:
pre-trained decoders consistently yield more fluent and accurate outputs, while
pre-trained encoders show varied effects depending on the quality of
visual-text alignment. Furthermore, we provide insights into the interplay
between modality fusion and pre-trained components, offering guidance for
future architecture design in multimodal translation systems.
