---
layout: publication
title: Evaluation of Language Models in the Medical Context Under Resource-Constrained Settings
authors: Posada Andrea, Rueckert Daniel, Meissen Felix, Müller Philip
conference: "Arxiv"
year: 2024
bibkey: posada2024evaluation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16611"}
  - {name: "Code", url: "https://github.com/anpoc/Language-models-in-medicine"}
tags: ['Applications', 'Fine Tuning', 'Has Code', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Survey Paper', 'Training Techniques', 'Transformer']
---
Since the emergence of the Transformer architecture language model development has increased driven by their promising potential. However releasing these models into production requires properly understanding their behavior particularly in sensitive domains such as medicine. Despite this need the medical literature still lacks technical assessments of pre-trained language models which are especially valuable in resource-constrained settings in terms of computational power or limited budget. To address this gap we provide a comprehensive survey of language models in the medical domain. In addition we selected a subset of these models for thorough evaluation focusing on classification and text generation tasks. Our subset encompasses 53 models ranging from 110 million to 13 billion parameters spanning the three families of Transformer-based models and from diverse knowledge domains. This study employs a series of approaches for text classification together with zero-shot prompting instead of model training or fine-tuning which closely resembles the limited resource setting in which many users of language models find themselves. Encouragingly our findings reveal remarkable performance across various tasks and datasets underscoring the latent potential of certain models to contain medical knowledge even without domain specialization. Consequently our study advocates for further exploration of model applications in medical contexts particularly in resource-constrained settings. The code is available on https://github.com/anpoc/Language-models-in-medicine.
