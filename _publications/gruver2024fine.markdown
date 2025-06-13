---
layout: publication
title: 'Fine-tuned Language Models Generate Stable Inorganic Materials As Text'
authors: Nate Gruver, Anuroop Sriram, Andrea Madotto, Andrew Gordon Wilson, C. Lawrence Zitnick, Zachary Ulissi
conference: "Arxiv"
year: 2024
bibkey: gruver2024fine
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.04379'}
tags: ['Training Techniques', 'Merging', 'Fine-Tuning', 'Prompting', 'Ethics and Bias', 'Pretraining Methods']
---
We propose fine-tuning large language models for generation of stable
materials. While unorthodox, fine-tuning large language models on text-encoded
atomistic data is simple to implement yet reliable, with around 90% of sampled
structures obeying physical constraints on atom positions and charges. Using
energy above hull calculations from both learned ML potentials and
gold-standard DFT calculations, we show that our strongest model (fine-tuned
LLaMA-2 70B) can generate materials predicted to be metastable at about twice
the rate (49% vs 28%) of CDVAE, a competing diffusion model. Because of text
prompting's inherent flexibility, our models can simultaneously be used for
unconditional generation of stable material, infilling of partial structures
and text-conditional generation. Finally, we show that language models' ability
to capture key symmetries of crystal structures improves with model scale,
suggesting that the biases of pretrained LLMs are surprisingly well-suited for
atomistic data.
