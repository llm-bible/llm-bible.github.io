---
layout: publication
title: 'PERFECT: Prompt-free And Efficient Few-shot Learning With Language Models'
authors: Rabeeh Karimi Mahabadi, Luke Zettlemoyer, James Henderson, Marzieh Saeidi, Lambert Mathias, Veselin Stoyanov, Majid Yazdani
conference: "Arxiv"
year: 2022
bibkey: mahabadi2022prompt
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2204.01172'}
  - {name: "Code", url: 'https://github.com/facebookresearch/perfect.git'}
tags: ['Masked Language Model', 'Has Code', 'Few-Shot', 'RAG', 'Training Techniques', 'BERT', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Current methods for few-shot fine-tuning of pretrained masked language models
(PLMs) require carefully engineered prompts and verbalizers for each new task
to convert examples into a cloze-format that the PLM can score. In this work,
we propose PERFECT, a simple and efficient method for few-shot fine-tuning of
PLMs without relying on any such handcrafting, which is highly effective given
as few as 32 data points. PERFECT makes two key design choices: First, we show
that manually engineered task prompts can be replaced with task-specific
adapters that enable sample-efficient fine-tuning and reduce memory and storage
costs by roughly factors of 5 and 100, respectively. Second, instead of using
handcrafted verbalizers, we learn new multi-token label embeddings during
fine-tuning, which are not tied to the model vocabulary and which allow us to
avoid complex auto-regressive decoding. These embeddings are not only learnable
from limited data but also enable nearly 100x faster training and inference.
Experiments on a wide range of few-shot NLP tasks demonstrate that PERFECT,
while being simple and efficient, also outperforms existing state-of-the-art
few-shot learning methods. Our code is publicly available at
https://github.com/facebookresearch/perfect.git.
