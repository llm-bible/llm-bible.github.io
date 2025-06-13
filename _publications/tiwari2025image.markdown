---
layout: publication
title: 'IMAGE-ALCHEMY: Advancing Subject Fidelity In Personalised Text-to-image Generation'
authors: Amritanshu Tiwari, Cherish Puniani, Kaustubh Sharma, Ojasva Nema
conference: "Arxiv"
year: 2025
bibkey: tiwari2025image
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.10743"}
tags: ['Fine-Tuning', 'Tools', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Recent advances in text-to-image diffusion models, particularly Stable Diffusion, have enabled the generation of highly detailed and semantically rich images. However, personalizing these models to represent novel subjects based on a few reference images remains challenging. This often leads to catastrophic forgetting, overfitting, or large computational overhead.We propose a two-stage pipeline that addresses these limitations by leveraging LoRA-based fine-tuning on the attention weights within the U-Net of the Stable Diffusion XL (SDXL) model. First, we use the unmodified SDXL to generate a generic scene by replacing the subject with its class label. Then, we selectively insert the personalized subject through a segmentation-driven image-to-image (Img2Img) pipeline that uses the trained LoRA weights.This framework isolates the subject encoding from the overall composition, thus preserving SDXL's broader generative capabilities while integrating the new subject in a high-fidelity manner. Our method achieves a DINO similarity score of 0.789 on SDXL, outperforming existing personalized text-to-image approaches.
