---
layout: publication
title: What If We Recaption Billions of Web Images with LLaMA-3
authors: Li Xianhang, Tu Haoqin, Hui Mude, Wang Zeyu, Zhao Bingchen, Xiao Junfei, Ren Sucheng, Mei Jieru, Liu Qing, Zheng Huangjie, Zhou Yuyin, Xie Cihang
conference: "Arxiv"
year: 2024
bibkey: li2024what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.08478"}
tags: ['GPT', 'Merging', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Web-crawled image-text pairs are inherently noisy. Prior studies demonstrate that semantically aligning and enriching textual descriptions of these pairs can significantly enhance model training across various vision-language tasks particularly text-to-image generation. However large-scale investigations in this area remain predominantly closed-source. Our paper aims to bridge this community effort leveraging the powerful and LLaMA-3 a GPT-4 level LLM. Our recaptioning pipeline is simple first we fine-tune a LLaMA-3-8B powered LLaVA-1.5 and then employ it to recaption 1.3 billion images from the DataComp-1B dataset. Our empirical results confirm that this enhanced dataset Recap-DataComp-1B offers substantial benefits in training advanced vision-language models. For discriminative models like CLIP we observe enhanced zero-shot performance in cross-modal retrieval tasks. For generative models like text-to-image Diffusion Transformers the generated images exhibit a significant improvement in alignment with users text instructions especially in following complex queries. Our project page is https://www.haqtu.me/Recap-Datacomp-1B/
