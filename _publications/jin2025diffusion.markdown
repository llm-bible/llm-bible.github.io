---
layout: publication
title: 'Diffusion Instruction Tuning'
authors: Chen Jin, Ryutaro Tanno, Amrutha Saseendran, Tom Diethe, Philip Teare
conference: "Arxiv"
year: 2025
bibkey: jin2025diffusion
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.06814"}
  - {name: "Code", url: "https://astrazeneca.github.io/vlm/"}
tags: ['Fine-Tuning', 'Transformer', 'RAG', 'Model Architecture', 'Merging', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods', 'Multimodal Models']
---
We introduce Lavender, a simple supervised fine-tuning (SFT) method that boosts the performance of advanced vision-language models (VLMs) by leveraging state-of-the-art image generation models such as Stable Diffusion. Specifically, Lavender aligns the text-vision attention in the VLM transformer with the equivalent used by Stable Diffusion during SFT, instead of adapting separate encoders. This alignment enriches the model's visual understanding and significantly boosts performance across in- and out-of-distribution tasks. Lavender requires just 0.13 million training examples, 2.5% of typical large-scale SFT datasets, and fine-tunes on standard hardware (8 GPUs) in a single day. It consistently improves state-of-the-art open-source multimodal LLMs (e.g., Llama-3.2-11B, MiniCPM-Llama3-v2.5), achieving up to 30% gains and a 68% boost on challenging out-of-distribution medical QA tasks. By efficiently transferring the visual expertise of image generators with minimal supervision, Lavender offers a scalable solution for more accurate vision-language systems. All code, training data, and models will be shared at https://astrazeneca.github.io/vlm/.
