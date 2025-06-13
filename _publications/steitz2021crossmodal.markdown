---
layout: publication
title: 'Txt: Crossmodal End-to-end Learning With Transformers'
authors: Jan-martin O. Steitz, Jonas Pfeiffer, Iryna Gurevych, Stefan Roth
conference: "Arxiv"
year: 2021
bibkey: steitz2021crossmodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.04422"}
tags: ['Fine-Tuning', 'Transformer', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
Reasoning over multiple modalities, e.g. in Visual Question Answering (VQA),
requires an alignment of semantic concepts across domains. Despite the
widespread success of end-to-end learning, today's multimodal pipelines by and
large leverage pre-extracted, fixed features from object detectors, typically
Faster R-CNN, as representations of the visual world. The obvious downside is
that the visual representation is not specifically tuned to the multimodal task
at hand. At the same time, while transformer-based object detectors have gained
popularity, they have not been employed in today's multimodal pipelines. We
address both shortcomings with TxT, a transformer-based crossmodal pipeline
that enables fine-tuning both language and visual components on the downstream
task in a fully end-to-end manner. We overcome existing limitations of
transformer-based detectors for multimodal reasoning regarding the integration
of global context and their scalability. Our transformer-based multimodal model
achieves considerable gains from end-to-end learning for multimodal question
answering.
