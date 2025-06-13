---
layout: publication
title: 'Diffusion Beats Autoregressive: An Evaluation Of Compositional Generation In Text-to-image Models'
authors: Arash Marioriyad, Parham Rezaei, Mahdieh Soleymani Baghshah, Mohammad Hossein Rohban
conference: "Arxiv"
year: 2024
bibkey: marioriyad2024diffusion
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.22775"}
tags: ['Reinforcement Learning', 'Language Modeling', 'Merging', 'GPT', 'Pretraining Methods', 'Prompting']
---
Text-to-image (T2I) generative models, such as Stable Diffusion and DALL-E,
have shown remarkable proficiency in producing high-quality, realistic, and
natural images from textual descriptions. However, these models sometimes fail
to accurately capture all the details specified in the input prompts,
particularly concerning entities, attributes, and spatial relationships. This
issue becomes more pronounced when the prompt contains novel or complex
compositions, leading to what are known as compositional generation failure
modes. Recently, a new open-source diffusion-based T2I model, FLUX, has been
introduced, demonstrating strong performance in high-quality image generation.
Additionally, autoregressive T2I models like LlamaGen have claimed competitive
visual quality performance compared to diffusion-based models. In this study,
we evaluate the compositional generation capabilities of these newly introduced
models against established models using the T2I-CompBench benchmark. Our
findings reveal that LlamaGen, as a vanilla autoregressive model, is not yet on
par with state-of-the-art diffusion models for compositional generation tasks
under the same criteria, such as model size and inference time. On the other
hand, the open-source diffusion-based model FLUX exhibits compositional
generation capabilities comparable to the state-of-the-art closed-source model
DALL-E3.
