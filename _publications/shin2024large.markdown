---
layout: publication
title: 'Large-scale Text-to-image Model With Inpainting Is A Zero-shot Subject-driven Image Generator'
authors: Chaehun Shin, Jooyoung Choi, Heeseung Kim, Sungroh Yoon
conference: "Arxiv"
year: 2024
bibkey: shin2024large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.15466'}
tags: ['Attention Mechanism', 'RAG', 'Training Techniques', 'Applications', 'Model Architecture', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Subject-driven text-to-image generation aims to produce images of a new subject within a desired context by accurately capturing both the visual characteristics of the subject and the semantic content of a text prompt. Traditional methods rely on time- and resource-intensive fine-tuning for subject alignment, while recent zero-shot approaches leverage on-the-fly image prompting, often sacrificing subject alignment. In this paper, we introduce Diptych Prompting, a novel zero-shot approach that reinterprets as an inpainting task with precise subject alignment by leveraging the emergent property of diptych generation in large-scale text-to-image models. Diptych Prompting arranges an incomplete diptych with the reference image in the left panel, and performs text-conditioned inpainting on the right panel. We further prevent unwanted content leakage by removing the background in the reference image and improve fine-grained details in the generated subject by enhancing attention weights between the panels during inpainting. Experimental results confirm that our approach significantly outperforms zero-shot image prompting methods, resulting in images that are visually preferred by users. Additionally, our method supports not only subject-driven generation but also stylized image generation and subject-driven image editing, demonstrating versatility across diverse image generation applications. Project page: https://diptychprompting.github.io/
