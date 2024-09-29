---
layout: publication
title: "Revision Transformers: Instructing Language Models To Change Their Values"
authors: Friedrich Felix, Stammer Wolfgang, Schramowski Patrick, Kersting Kristian
conference: "Arxiv"
year: 2022
bibkey: friedrich2022revision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.10332"}
tags: ['Ethics And Bias', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Current transformer language models (LM) are large-scale models with billions of parameters. They have been shown to provide high performances on a variety of tasks but are also prone to shortcut learning and bias. Addressing such incorrect model behavior via parameter adjustments is very costly. This is particularly problematic for updating dynamic concepts such as moral values which vary culturally or interpersonally. In this work we question the current common practice of storing all information in the model parameters and propose the Revision Transformer (RiT) to facilitate easy model updating. The specific combination of a large-scale pre-trained LM that inherently but also diffusely encodes world knowledge with a clear-structured revision engine makes it possible to update the models knowledge with little effort and the help of user interaction. We exemplify RiT on a moral dataset and simulate user feedback demonstrating strong performance in model revision even with small data. This way users can easily design a model regarding their preferences paving the way for more transparent AI models.
