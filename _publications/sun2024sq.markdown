---
layout: publication
title: Sq-llava: Self-questioning For Large Vision-language Assistant
authors: Sun Guohao, Qin Can, Wang Jiamian, Chen Zeyuan, Xu Ran, Tao Zhiqiang
conference: "Arxiv"
year: 2024
bibkey: sun2024sq
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.11299"}
tags: ['Fine Tuning', 'Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Recent advances in vision-language models have shown notable generalization in broad tasks through visual instruction tuning. However bridging the gap between the pre-trained vision encoder and the large language models (LLMs) becomes the whole networks bottleneck. To improve cross-modality alignment existing works usually consider more visual instruction data covering a broader range of vision tasks to fine-tune the model for question-answering which however is costly to obtain and has not thoroughly explored the rich contextual information contained in images. This paper first attempts to harness the overlooked context within visual instruction data training the model to self-supervised learning how to ask high-quality questions. In this way we introduce a novel framework named SQ-LLaVA Self-Questioning for Large Vision-Language Assistant. SQ-LLaVA exhibits proficiency in generating flexible and meaningful image-related questions while analyzing the visual clue and prior language knowledge signifying an advanced level of generalized visual understanding. Moreover fine-tuning SQ-LLaVA on higher-quality instruction data shows a performance improvement compared with traditional visual-instruction tuning methods. This improvement highlights the efficacy of self-questioning techniques in achieving a deeper and more nuanced comprehension of visual content across various contexts.
