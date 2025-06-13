---
layout: publication
title: 'Qwen Look Again: Guiding Vision-language Reasoning Models To Re-attention Visual Information'
authors: Xu Chu, Xinrong Chen, Guanyu Wang, Zhijie Tan, Kui Huang, Wenyu Lv, Tong Mo, Weiping Li
conference: "Arxiv"
year: 2025
bibkey: chu2025qwen
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.23558'}
  - {name: "Code", url: 'https://github.com/Liar406/Look_Again'}
tags: ['Attention Mechanism', 'Agentic', 'Has Code', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
Inference time scaling drives extended reasoning to enhance the performance of Vision-Language Models (VLMs), thus forming powerful Vision-Language Reasoning Models (VLRMs). However, long reasoning dilutes visual tokens, causing visual information to receive less attention and may trigger hallucinations. Although introducing text-only reflection processes shows promise in language models, we demonstrate that it is insufficient to suppress hallucinations in VLMs. To address this issue, we introduce Qwen-LookAgain (Qwen-LA), a novel VLRM designed to mitigate hallucinations by incorporating a vision-text reflection process that guides the model to re-attention visual information during reasoning. We first propose a reinforcement learning method Balanced Reflective Policy Optimization (BRPO), which guides the model to decide when to generate vision-text reflection on its own and balance the number and length of reflections. Then, we formally prove that VLRMs lose attention to visual tokens as reasoning progresses, and demonstrate that supplementing visual information during reflection enhances visual attention. Therefore, during training and inference, Visual Token COPY and Visual Token ROUTE are introduced to force the model to re-attention visual information at the visual level, addressing the limitations of text-only reflection. Experiments on multiple visual QA datasets and hallucination metrics indicate that Qwen-LA achieves leading accuracy performance while reducing hallucinations. Our code is available at: https://github.com/Liar406/Look_Again
