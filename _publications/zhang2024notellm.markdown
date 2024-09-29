---
layout: publication
title: Notellm-2&#58; Multimodal Large Representation Models For Recommendation
authors: Zhang Chao, Zhang Haoxin, Wu Shiwei, Wu Di, Xu Tong, Gao Yan, Hu Yao, Chen Enhong
conference: "Arxiv"
year: 2024
bibkey: zhang2024notellm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16789"}
tags: ['Merging', 'Model Architecture', 'Multimodal Models', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) have demonstrated exceptional text understanding. Existing works explore their application in text embedding tasks. However there are few works utilizing LLMs to assist multimodal representation tasks. In this work we investigate the potential of LLMs to enhance multimodal representation in multimodal item-to-item (I2I) recommendations. One feasible method is the transfer of Multimodal Large Language Models (MLLMs) for representation tasks. However pre-training MLLMs usually requires collecting high-quality web-scale multimodal data resulting in complex training procedures and high costs. This leads the community to rely heavily on open-source MLLMs hindering customized training for representation scenarios. Therefore we aim to design an end-to-end training method that customizes the integration of any existing LLMs and vision encoders to construct efficient multimodal representation models. Preliminary experiments show that fine-tuned LLMs in this end-to-end method tend to overlook image content. To overcome this challenge we propose a novel training framework NoteLLM-2 specifically designed for multimodal representation. We propose two ways to enhance the focus on visual information. The first method is based on the prompt viewpoint which separates multimodal content into visual content and textual content. NoteLLM-2 adopts the multimodal In-Content Learning method to teach LLMs to focus on both modalities and aggregate key information. The second method is from the model architecture utilizing a late fusion mechanism to directly fuse visual information into textual information. Extensive experiments have been conducted to validate the effectiveness of our method.
