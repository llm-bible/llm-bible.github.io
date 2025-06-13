---
layout: publication
title: 'QLIP: A Dynamic Quadtree Vision Prior Enhances MLLM Performance Without Retraining'
authors: Kyle R. Chickering, Bangzheng Li, Muhao Chen
conference: "Arxiv"
year: 2025
bibkey: chickering2025dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.23004"}
tags: ['Fine-Tuning', 'Ethics and Bias', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
Multimodal Large Language Models (MLLMs) encode images into visual tokens, aligning visual and textual signals within a shared latent space to facilitate crossmodal representation learning. The CLIP model is a widely adopted foundational vision language model whose vision encoder has played a critical role in the development of MLLMs such as LLaVA. However, the CLIP vision encoder suffers from notable limitations including being constrained to only handling fixed input resolutions and a failure to produce separated embeddings for dissimilar images. Replacing the vision encoder of an existing model typically incurs substantial computational costs because such a change often necessitates retraining the entire model pipeline.
  In this work, we identify two factors which underlie the limitations of the CLIP vision encoder: mesoscopic bias and interpolation bias. To address these issues, we propose QLIP, a drop-in replacement for CLIP that can be seamlessly integrated with existing MLLMs with only a few lines of code and can enhance both coarse-grained and fine-grained visual understanding, without re-training. QLIP is designed around an image quadtree which replaces the standard uniform grid patches with a novel content aware patchification. Our experimental results demonstrate that QLIP improves the general visual question answering accuracy of the LLaVA v1.5 model series across various model sizes--without requiring retraining or fine-tuning of the full MLLM. Notably, QLIP boosts detailed understanding performance on the challenging \\(V^\{\ast\}\\) benchmark by up to 13.6 percent.
