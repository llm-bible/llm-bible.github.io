---
layout: publication
title: 'GLOV: Guided Large Language Models As Implicit Optimizers For Vision Language Models'
authors: M. Jehanzeb Mirza, Mengjie Zhao, Zhuoyuan Mao, Sivan Doveh, Wei Lin, Paul Gavrikov, Michael Dorkenwald, Shiqi Yang, Saurav Jha, Hiromi Wakaki, Yuki Mitsufuji, Horst Possegger, Rogerio Feris, Leonid Karlinsky, James Glass
conference: "Arxiv"
year: 2024
bibkey: mirza2024guided
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.06154"}
tags: ['Responsible AI', 'Efficiency and Optimization', 'Ethics and Bias', 'Security', 'Multimodal Models', 'Prompting']
---
In this work, we propose GLOV, which enables Large Language Models (LLMs) to
act as implicit optimizers for Vision-Language Models (VLMs) to enhance
downstream vision tasks. GLOV prompts an LLM with the downstream task
description, querying it for suitable VLM prompts (e.g., for zero-shot
classification with CLIP). These prompts are ranked according to their fitness
for the downstream vision task. In each respective optimization step, the
ranked prompts are fed as in-context examples (with their accuracies) to equip
the LLM with the knowledge of the type of prompts preferred by the downstream
VLM. Furthermore, we explicitly guide the LLM's generation at each optimization
step by adding an offset vector -- calculated from the embedding differences
between previous positive and negative solutions -- to the intermediate layer
of the network for the next generation. This offset vector biases the LLM
generation toward the type of language the downstream VLM prefers, resulting in
enhanced performance on the downstream vision tasks. We comprehensively
evaluate our GLOV on two tasks: object recognition and the critical task of
enhancing VLM safety. Our GLOV shows performance improvement by up to 15.0% and
57.5% for dual-encoder (e.g., CLIP) and encoder-decoder (e.g., LlaVA) models
for object recognition and reduces the attack success rate (ASR) on
state-of-the-art VLMs by up to \\(60.7%\\).
