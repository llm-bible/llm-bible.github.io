---
layout: publication
title: 'Do You Keep An Eye On What I Ask? Mitigating Multimodal Hallucination Via Attention-guided Ensemble Decoding'
authors: Yeongjae Cho, Keonwoo Kim, Taebaek Hwang, Sungzoon Cho
conference: "Arxiv"
year: 2025
bibkey: cho2025do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17529"}
tags: ['Applications', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Multimodal Models']
---
Recent advancements in Large Vision-Language Models (LVLMs) have significantly expanded their utility in tasks like image captioning and visual question answering. However, they still struggle with object hallucination, where models generate descriptions that inaccurately reflect the visual content by including nonexistent objects or misrepresenting existing ones. While previous methods, such as data augmentation and training-free approaches, strive to tackle this issue, they still encounter scalability challenges and often depend on additional external modules. In this work, we propose Ensemble Decoding (ED), a novel strategy that splits the input image into sub-images and combines logit distributions by assigning weights through the attention map. Furthermore, we introduce ED adaptive plausibility constraint to calibrate logit distribution and FastED, a variant designed for speed-critical applications. Extensive experiments across hallucination benchmarks demonstrate that our proposed method achieves state-of-the-art performance, validating the effectiveness of our approach.
