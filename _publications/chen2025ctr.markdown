---
layout: publication
title: 'Ctr-driven Advertising Image Generation With Multimodal Large Language Models'
authors: Xingye Chen, Wei Feng, Zhenbang Du, Weizhen Wang, Yanyin Chen, Haohan Wang, Linkai Liu, Yaoyu Li, Jinyuan Zhao, Yu Li, Zheng Zhang, Jingjing Lv, Junjie Shen, Zhangang Lin, Jingping Shao, Yuanjie Shao, Xinge You, Changxin Gao, Nong Sang
conference: "Arxiv"
year: 2025
bibkey: chen2025ctr
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.06823'}
  - {name: "Code", url: 'https://github.com/Chenguoz/CAIG'}
tags: ['Attention Mechanism', 'Agentic', 'Has Code', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Fine-Tuning', 'Multimodal Models', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
In web data, advertising images are crucial for capturing user attention and
improving advertising effectiveness. Most existing methods generate background
for products primarily focus on the aesthetic quality, which may fail to
achieve satisfactory online performance. To address this limitation, we explore
the use of Multimodal Large Language Models (MLLMs) for generating advertising
images by optimizing for Click-Through Rate (CTR) as the primary objective.
Firstly, we build targeted pre-training tasks, and leverage a large-scale
e-commerce multimodal dataset to equip MLLMs with initial capabilities for
advertising image generation tasks. To further improve the CTR of generated
images, we propose a novel reward model to fine-tune pre-trained MLLMs through
Reinforcement Learning (RL), which can jointly utilize multimodal features and
accurately reflect user click preferences. Meanwhile, a product-centric
preference optimization strategy is developed to ensure that the generated
background content aligns with the product characteristics after fine-tuning,
enhancing the overall relevance and effectiveness of the advertising images.
Extensive experiments have demonstrated that our method achieves
state-of-the-art performance in both online and offline metrics. Our code and
pre-trained models are publicly available at: https://github.com/Chenguoz/CAIG.
