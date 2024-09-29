---
layout: publication
title: What If We Recaption Billions Of Web Images With Llama45;3
authors: Li Xianhang, Tu Haoqin, Hui Mude, Wang Zeyu, Zhao Bingchen, Xiao Junfei, Ren Sucheng, Mei Jieru, Liu Qing, Zheng Huangjie, Zhou Yuyin, Xie Cihang
conference: "Arxiv"
year: 2024
bibkey: li2024what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.08478"}
tags: ['GPT', 'Merging', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Web45;crawled image45;text pairs are inherently noisy. Prior studies demonstrate that semantically aligning and enriching textual descriptions of these pairs can significantly enhance model training across various vision45;language tasks particularly text45;to45;image generation. However large45;scale investigations in this area remain predominantly closed45;source. Our paper aims to bridge this community effort leveraging the powerful and textit123;open45;sourced125; LLaMA45;3 a GPT45;4 level LLM. Our recaptioning pipeline is simple first we fine45;tune a LLaMA45;345;8B powered LLaVA45;1.5 and then employ it to recaption 1.3 billion images from the DataComp45;1B dataset. Our empirical results confirm that this enhanced dataset Recap45;DataComp45;1B offers substantial benefits in training advanced vision45;language models. For discriminative models like CLIP we observe enhanced zero45;shot performance in cross45;modal retrieval tasks. For generative models like text45;to45;image Diffusion Transformers the generated images exhibit a significant improvement in alignment with users text instructions especially in following complex queries. Our project page is https://www.haqtu.me/Recap&#45;Datacomp&#45;1B/
