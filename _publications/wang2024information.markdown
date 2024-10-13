---
layout: publication
title: 'Information Theoretic Text-to-image Alignment'
authors: Wang Chao, Franzese Giulio, Finamore Alessandro, Gallo Massimo, Michiardi Pietro
conference: "Arxiv"
year: 2024
bibkey: wang2024information
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.20759"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Merging', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Diffusion models for Text-to-Image (T2I) conditional generation have seen
tremendous success recently. Despite their success, accurately capturing user
intentions with these models still requires a laborious trial and error
process. This challenge is commonly identified as a model alignment problem, an
issue that has attracted considerable attention by the research community.
Instead of relying on fine-grained linguistic analyses of prompts, human
annotation, or auxiliary vision-language models to steer image generation, in
this work we present a novel method that relies on an information-theoretic
alignment measure. In a nutshell, our method uses self-supervised fine-tuning
and relies on point-wise mutual information between prompts and images to
define a synthetic training set to induce model alignment. Our comparative
analysis shows that our method is on-par or superior to the state-of-the-art,
yet requires nothing but a pre-trained denoising network to estimate MI and a
lightweight fine-tuning strategy.
