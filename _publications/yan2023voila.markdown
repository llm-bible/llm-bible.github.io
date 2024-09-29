---
layout: publication
title: "Voila-a: Aligning Vision-language Models With User's Gaze Attention"
authors: Yan Kun, Ji Lei, Wang Zeyu, Wang Yuntao, Duan Nan, Ma Shuai
conference: "Arxiv"
year: 2023
bibkey: yan2023voila
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.09454"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
In recent years the integration of vision and language understanding has led to significant advancements in artificial intelligence particularly through Vision-Language Models (VLMs). However existing VLMs face challenges in handling real-world applications with complex scenes and multiple objects as well as aligning their focus with the diverse attention patterns of human users. In this paper we introduce gaze information feasibly collected by AR or VR devices as a proxy for human attention to guide VLMs and propose a novel approach Voila-A for gaze alignment to enhance the interpretability and effectiveness of these models in real-world applications. First we collect hundreds of minutes of gaze data to demonstrate that we can mimic human gaze modalities using localized narratives. We then design an automatic data annotation pipeline utilizing GPT-4 to generate the VOILA-COCO dataset. Additionally we innovate the Voila Perceiver modules to integrate gaze information into VLMs while preserving their pretrained knowledge. We evaluate Voila-A using a hold-out validation set and a newly collected VOILA-GAZE Testset which features real-life scenarios captured with a gaze-tracking device. Our experimental results demonstrate that Voila-A significantly outperforms several baseline models. By aligning model attention with human gaze patterns Voila-A paves the way for more intuitive user-centric VLMs and fosters engaging human-AI interaction across a wide range of applications.
