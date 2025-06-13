---
layout: publication
title: 'Evaluation Of Language Models In The Medical Context Under Resource-constrained Settings'
authors: Andrea Posada, Daniel Rueckert, Felix Meissen, Philip Müller
conference: "Arxiv"
year: 2024
bibkey: posada2024evaluation
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.16611'}
  - {name: "Code", url: 'https://github.com/anpoc/Language-models-in-medicine'}
tags: ['Has Code', 'Language Modeling', 'Transformer', 'Applications', 'Model Architecture', 'Fine-Tuning', 'Survey Paper', 'Reinforcement Learning', 'Pretraining Methods']
---
Since the Transformer architecture emerged, language model development has
grown, driven by their promising potential. Releasing these models into
production requires properly understanding their behavior, particularly in
sensitive domains like medicine. Despite this need, the medical literature
still lacks practical assessment of pre-trained language models, which are
especially valuable in settings where only consumer-grade computational
resources are available. To address this gap, we have conducted a comprehensive
survey of language models in the medical field and evaluated a subset of these
for medical text classification and conditional text generation. The subset
includes 53 models with 110 million to 13 billion parameters, spanning the
Transformer-based model families and knowledge domains. Different approaches
are employed for text classification, including zero-shot learning, enabling
tuning without the need to train the model. These approaches are helpful in our
target settings, where many users of language models find themselves. The
results reveal remarkable performance across the tasks and datasets evaluated,
underscoring the potential of certain models to contain medical knowledge, even
without domain specialization. This study thus advocates for further
exploration of model applications in medical contexts, particularly in
computational resource-constrained settings, to benefit a wide range of users.
The code is available on https://github.com/anpoc/Language-models-in-medicine.
