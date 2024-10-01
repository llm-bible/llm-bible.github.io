---
layout: publication
title: 'Kosmos-g: Generating Images In Context With Multimodal Large Language Models'
authors: Pan Xichen, Dong Li, Huang Shaohan, Peng Zhiliang, Chen Wenhu, Wei Furu
conference: "Arxiv"
year: 2023
bibkey: pan2023kosmos
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.02992"}
  - {name: "Code", url: "https://aka.ms/Kosmos-G"}
tags: ['Distillation', 'Efficiency And Optimization', 'Has Code', 'Multimodal Models', 'RAG', 'Reinforcement Learning']
---
"Recent advancements in subject-driven image generation have made significant strides. However, current methods still fall short in diverse application scenarios, as they require test-time tuning and cannot accept interleaved multi-image and text input. These limitations keep them far from the ultimate goal of image as a foreign language in image generation. This paper presents Kosmos-G, a model that leverages the advanced multimodal perception capabilities of Multimodal Large Language Models (MLLMs) to tackle the aforementioned challenge. Our approach aligns the output space of MLLM with CLIP using the textual modality as an anchor and performs compositional instruction tuning on curated data. Kosmos-G demonstrates an impressive capability of zero-shot subject-driven generation with interleaved multi-image and text input. Notably, the score distillation instruction tuning requires no modifications to the image decoder. This allows for a seamless substitution of CLIP and effortless integration with a myriad of U-Net techniques ranging from fine-grained controls to personalized image decoder variants. We posit Kosmos-G as an initial attempt towards the goal of image as a foreign language in image generation. The code can be found at https://aka.ms/Kosmos-G"
