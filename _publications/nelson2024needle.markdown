---
layout: publication
title: 'Needle In The Haystack For Memory Based Large Language Models'
authors: Elliot Nelson, Georgios Kollias, Payel Das, Subhajit Chaudhury, Soham Dan
conference: "Arxiv"
year: 2024
bibkey: nelson2024needle
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.01437'}
tags: ['Attention Mechanism', 'Transformer', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Current large language models (LLMs) often perform poorly on simple fact
retrieval tasks. Here we investigate if coupling a dynamically adaptable
external memory to a LLM can alleviate this problem. For this purpose, we test
Larimar, a recently proposed language model architecture which uses an external
associative memory, on long-context recall tasks including passkey and
needle-in-the-haystack tests. We demonstrate that the external memory of
Larimar, which allows fast write and read of an episode of text samples, can be
used at test time to handle contexts much longer than those seen during
training. We further show that the latent readouts from the memory (to which
long contexts are written) control the decoder towards generating correct
outputs, with the memory stored off of the GPU. Compared to existing
transformer-based LLM architectures for long-context recall tasks that use
larger parameter counts or modified attention mechanisms, a relatively smaller
size Larimar is able to maintain strong performance without any task-specific
training or training on longer contexts.
