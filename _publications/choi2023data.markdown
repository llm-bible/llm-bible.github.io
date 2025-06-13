---
layout: publication
title: 'ODIN: On-demand Data Formulation To Mitigate Dataset Lock-in'
authors: Sp Choi, Jihun Lee, Hyeongseok Ahn, Sanghee Jung, Bumsoo Kang
conference: "Arxiv"
year: 2023
bibkey: choi2023data
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.06832"}
tags: ['GPT', 'Model Architecture', 'Merging', 'Training Techniques', 'Prompting']
---
ODIN is an innovative approach that addresses the problem of dataset
constraints by integrating generative AI models. Traditional zero-shot learning
methods are constrained by the training dataset. To fundamentally overcome this
limitation, ODIN attempts to mitigate the dataset constraints by generating
on-demand datasets based on user requirements. ODIN consists of three main
modules: a prompt generator, a text-to-image generator, and an image
post-processor. To generate high-quality prompts and images, we adopted a large
language model (e.g., ChatGPT), and a text-to-image diffusion model (e.g.,
Stable Diffusion), respectively. We evaluated ODIN on various datasets in terms
of model accuracy and data diversity to demonstrate its potential, and
conducted post-experiments for further investigation. Overall, ODIN is a
feasible approach that enables Al to learn unseen knowledge beyond the training
dataset.
