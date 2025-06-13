---
layout: publication
title: 'You Can Remove Gpt2''s Layernorm By Fine-tuning'
authors: Stefan Heimersheim
conference: "Arxiv"
year: 2024
bibkey: heimersheim2024you
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.13710'}
  - {name: "Code", url: 'https://github.com/ApolloResearch/gpt2_noLN,'}
tags: ['Has Code', 'Interpretability and Explainability', 'Transformer', 'Training Techniques', 'Model Architecture', 'GPT', 'Fine-Tuning', 'Pretraining Methods']
---
The LayerNorm (LN) layer in GPT-style transformer models has long been a
hindrance to mechanistic interpretability. LN is a crucial component required
to stabilize the training of large language models, and LN or the similar
RMSNorm have been used in practically all large language models based on the
transformer architecture. The non-linear nature of the LN layers is a hindrance
for mechanistic interpretability as it hinders interpretation of the residual
stream, and makes it difficult to decompose the model into circuits. Some
researchers have gone so far as to name "reasons interpretability researchers
hate layer norm."
  In this paper we show that it is possible to remove the LN layers from a
pre-trained GPT2-small model by fine-tuning on a fraction (500M tokens) of the
training data. We demonstrate that this LN-free model achieves similar
performance to the original model on the OpenWebText and ThePile datasets
(-0.05 cross-entropy loss), and the Hellaswag benchmark (-0.5% accuracy). We
provide our implementation at https://github.com/ApolloResearch/gpt2_noLN, and
fine-tuned GPT2-small models at
https://huggingface.co/apollo-research/gpt2_noLN.
  Our work not only provides a simplified model for mechanistic
interpretability research, but also provides evidence that the LN layers, at
inference time, do not play a crucial role in transformer models.
