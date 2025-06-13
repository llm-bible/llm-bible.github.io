---
layout: publication
title: 'Scaling Vision Transformers To 22 Billion Parameters'
authors: Mostafa Dehghani, Josip Djolonga, Basil Mustafa, Piotr Padlewski, Jonathan Heek, Justin Gilmer, Andreas Steiner, Mathilde Caron, Robert Geirhos, Ibrahim Alabdulmohsin, Rodolphe Jenatton, Lucas Beyer, Michael Tschannen, Anurag Arnab, Xiao Wang, Carlos Riquelme, Matthias Minderer, Joan Puigcerver, Utku Evci, Manoj Kumar, Sjoerd Van Steenkiste, Gamaleldin F. Elsayed, Aravindh Mahendran, Fisher Yu, Avital Oliver, Fantine Huot, Jasmijn Bastings, Mark Patrick Collier, Alexey Gritsenko, Vighnesh Birodkar, Cristina Vasconcelos, Yi Tay, Thomas Mensink, Alexander Kolesnikov, Filip Pavetić, Dustin Tran, Thomas Kipf, Mario Lučić, Xiaohua Zhai, Daniel Keysers, Jeremiah Harmsen, Neil Houlsby
conference: "Arxiv"
year: 2023
bibkey: dehghani2023scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.05442"}
tags: ['Security', 'Model Architecture', 'Training Techniques', 'Fairness', 'Multimodal Models', 'Reinforcement Learning', 'Bias Mitigation', 'Ethics and Bias', 'Pretraining Methods', 'Transformer']
---
The scaling of Transformers has driven breakthrough capabilities for language
models. At present, the largest large language models (LLMs) contain upwards of
100B parameters. Vision Transformers (ViT) have introduced the same
architecture to image and video modelling, but these have not yet been
successfully scaled to nearly the same degree; the largest dense ViT contains
4B parameters (Chen et al., 2022). We present a recipe for highly efficient and
stable training of a 22B-parameter ViT (ViT-22B) and perform a wide variety of
experiments on the resulting model. When evaluated on downstream tasks (often
with a lightweight linear model on frozen features), ViT-22B demonstrates
increasing performance with scale. We further observe other interesting
benefits of scale, including an improved tradeoff between fairness and
performance, state-of-the-art alignment to human visual perception in terms of
shape/texture bias, and improved robustness. ViT-22B demonstrates the potential
for "LLM-like" scaling in vision, and provides key steps towards getting there.
