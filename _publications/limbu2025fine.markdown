---
layout: publication
title: 'Medblip: Fine-tuning BLIP For Medical Image Captioning'
authors: Manshi Limbu, Diwita Banerjee
conference: "Arxiv"
year: 2025
bibkey: limbu2025fine
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.14726'}
tags: ['Attention Mechanism', 'Interpretability and Explainability', 'Transformer', 'Training Techniques', 'Applications', 'Model Architecture', 'Fine-Tuning', 'GPT', 'Multimodal Models', 'Pretraining Methods']
---
Medical image captioning is a challenging task that requires generating clinically accurate and semantically meaningful descriptions of radiology images. While recent vision-language models (VLMs) such as BLIP, BLIP2, Gemini and ViT-GPT2 show strong performance on natural image datasets, they often produce generic or imprecise captions when applied to specialized medical domains. In this project, we explore the effectiveness of fine-tuning the BLIP model on the ROCO dataset for improved radiology captioning. We compare the fine-tuned BLIP against its zero-shot version, BLIP-2 base, BLIP-2 Instruct and a ViT-GPT2 transformer baseline. Our results demonstrate that domain-specific fine-tuning on BLIP significantly improves performance across both quantitative and qualitative evaluation metrics. We also visualize decoder cross-attention maps to assess interpretability and conduct an ablation study to evaluate the contributions of encoder-only and decoder-only fine-tuning. Our findings highlight the importance of targeted adaptation for medical applications and suggest that decoder-only fine-tuning (encoder-frozen) offers a strong performance baseline with 5% lower training time than full fine-tuning, while full model fine-tuning still yields the best results overall.
