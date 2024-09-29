---
layout: publication
title: Fine-tuned Language Models Generate Stable Inorganic Materials As Text
authors: Gruver Nate, Sriram Anuroop, Madotto Andrea, Wilson Andrew Gordon, Zitnick C. Lawrence, Ulissi Zachary
conference: "Arxiv"
year: 2024
bibkey: gruver2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.04379"}
tags: ['Ethics And Bias', 'Fine Tuning', 'Merging', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
We propose fine-tuning large language models for generation of stable materials. While unorthodox fine-tuning large language models on text-encoded atomistic data is simple to implement yet reliable with around 9037; of sampled structures obeying physical constraints on atom positions and charges. Using energy above hull calculations from both learned ML potentials and gold-standard DFT calculations we show that our strongest model (fine-tuned LLaMA-2 70B) can generate materials predicted to be metastable at about twice the rate (4937; vs 2837;) of CDVAE a competing diffusion model. Because of text promptings inherent flexibility our models can simultaneously be used for unconditional generation of stable material infilling of partial structures and text-conditional generation. Finally we show that language models ability to capture key symmetries of crystal structures improves with model scale suggesting that the biases of pretrained LLMs are surprisingly well-suited for atomistic data.
