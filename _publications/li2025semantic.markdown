---
layout: publication
title: 'Semantic-clipping: Efficient Vision-language Modeling With Semantic-guidedd Visual Selection'
authors: Bangzheng Li, Fei Wang, Wenxuan Zhou, Nan Xu, Ben Zhou, Sheng Zhang, Hoifung Poon, Muhao Chen
conference: "Arxiv"
year: 2025
bibkey: li2025semantic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.11794"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Multimodal Models', 'Tools', 'Reinforcement Learning', 'RAG', 'Language Modeling', 'Applications']
---
Vision-Language Models (VLMs) leverage aligned visual encoders to transform
images into visual tokens, allowing them to be processed similarly to text by
the backbone large language model (LLM). This unified input paradigm enables
VLMs to excel in vision-language tasks such as visual question answering (VQA).
To improve fine-grained visual reasoning, recent advancements in
vision-language modeling introduce image cropping techniques that feed all
encoded sub-images into the model. However, this approach significantly
increases the number of visual tokens, leading to inefficiency and potential
distractions for the LLM. To address the generalization challenges of image
representation in VLMs, we propose a lightweight, universal framework that
seamlessly integrates with existing VLMs to enhance their ability to process
finegrained details. Our method leverages textual semantics to identify key
visual areas, improving VQA performance without requiring any retraining of the
VLM. Additionally, it incorporates textual signals into the visual encoding
process, enhancing both efficiency and effectiveness. The proposed method,
SEMCLIP, strengthens the visual understanding of a 7B VLM, LLaVA-1.5 by 3.3% on
average across 7 benchmarks, and particularly by 5.3% on the challenging
detailed understanding benchmark V*.
