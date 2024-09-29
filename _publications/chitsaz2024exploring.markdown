---
layout: publication
title: Exploring Quantization For Efficient Pre45;training Of Transformer Language Models
authors: Chitsaz Kamran, Fournier Quentin, Mordido Gonçalo, Chandar Sarath
conference: "Arxiv"
year: 2024
bibkey: chitsaz2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.11722"}
  - {name: "Code", url: "https://github.com/chandar&#45;lab/EfficientLLMs"}
tags: ['Efficiency And Optimization', 'Has Code', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'Training Techniques', 'Transformer']
---
The increasing scale of Transformer models has led to an increase in their pre45;training computational requirements. While quantization has proven to be effective after pre45;training and during fine45;tuning applying quantization in Transformers during pre45;training has remained largely unexplored at scale for language modeling. This study aims to explore the impact of quantization for efficient pre45;training of Transformers with a focus on linear layer components. By systematically applying straightforward linear quantization to weights activations gradients and optimizer states we assess its effects on model efficiency stability and performance during training. By offering a comprehensive recipe of effective quantization strategies to be applied during the pre45;training of Transformers we promote high training efficiency from scratch while retaining language modeling ability. Code is available at https://github.com/chandar&#45;lab/EfficientLLMs.
