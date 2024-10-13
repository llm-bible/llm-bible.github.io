---
layout: publication
title: 'CTRL: A Conditional Transformer Language Model For Controllable Generation'
authors: Keskar Nitish Shirish, Mccann Bryan, Varshney Lav R., Xiong Caiming, Socher Richard
conference: "Arxiv"
year: 2019
bibkey: keskar2019conditional
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.05858"}
  - {name: "Code", url: "https://github.com/salesforce/ctrl"}
tags: ['Applications', 'Has Code', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Large-scale language models show promising text generation capabilities, but
users cannot easily control particular aspects of the generated text. We
release CTRL, a 1.63 billion-parameter conditional transformer language model,
trained to condition on control codes that govern style, content, and
task-specific behavior. Control codes were derived from structure that
naturally co-occurs with raw text, preserving the advantages of unsupervised
learning while providing more explicit control over text generation. These
codes also allow CTRL to predict which parts of the training data are most
likely given a sequence. This provides a potential method for analyzing large
amounts of data via model-based source attribution. We have released multiple
full-sized, pretrained versions of CTRL at https://github.com/salesforce/ctrl.
