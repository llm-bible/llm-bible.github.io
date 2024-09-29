---
layout: publication
title: In45;context Vectors Making In Context Learning More Effective And Controllable Through Latent Space Steering
authors: Liu Sheng, Ye Haotian, Xing Lei, Zou James
conference: "Arxiv"
year: 2023
bibkey: liu2023making
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.06668"}
tags: ['Prompting', 'Responsible AI']
---
Large language models (LLMs) demonstrate emergent in45;context learning capabilities where they adapt to new tasks based on example demonstrations. However in45;context learning has seen limited effectiveness in many settings is difficult to quantitatively control and takes up context window space. To overcome these limitations we propose an alternative approach that recasts in45;context learning as in45;context vectors (ICV). Using ICV has two steps. We first use a forward pass on demonstration examples to create the in45;context vector from the latent embedding of the LLM. This vector captures essential information about the intended task. On a new query instead of adding demonstrations to the prompt we shift the latent states of the LLM using the ICV. The ICV approach has several benefits 1) it enables the LLM to more effectively follow the demonstration examples; 2) its easy to control by adjusting the magnitude of the ICV; 3) it reduces the length of the prompt by removing the in45;context demonstrations; 4) ICV is computationally much more efficient than fine45;tuning. We demonstrate that ICV achieves better performance compared to standard in45;context learning and fine45;tuning on diverse tasks including safety style transfer role45;playing and formatting. Moreover we show that we can flexibly teach LLM to simultaneously follow different types of instructions by simple vector arithmetics on the corresponding ICVs.
