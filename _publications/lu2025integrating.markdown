---
layout: publication
title: 'Genieblue: Integrating Both Linguistic And Multimodal Capabilities For Large Language Models On Mobile Devices'
authors: Xudong Lu, Yinghao Chen, Renshou Wu, Haohao Gao, Xi Chen, Xue Yang, Xiangyu Zhao, Aojun Zhou, Fangyuan Li, Yafei Wen, Xiaoxin Chen, Shuai Ren, Hongsheng Li
conference: "Arxiv"
year: 2025
bibkey: lu2025integrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.06019"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Multimodal Models', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Applications']
---
Recent advancements in Multimodal Large Language Models (MLLMs) have enabled
their deployment on mobile devices. However, challenges persist in maintaining
strong language capabilities and ensuring hardware compatibility, both of which
are crucial for user experience and practical deployment efficiency. In our
deployment process, we observe that existing MLLMs often face performance
degradation on pure language tasks, and the current NPU platforms on
smartphones do not support the MoE architecture, which is commonly used to
preserve pure language capabilities during multimodal training. To address
these issues, we systematically analyze methods to maintain pure language
capabilities during the training of MLLMs, focusing on both training data and
model architecture aspects. Based on these analyses, we propose GenieBlue, an
efficient MLLM structural design that integrates both linguistic and multimodal
capabilities for LLMs on mobile devices. GenieBlue freezes the original LLM
parameters during MLLM training to maintain pure language capabilities. It
acquires multimodal capabilities by duplicating specific transformer blocks for
full fine-tuning and integrating lightweight LoRA modules. This approach
preserves language capabilities while achieving comparable multimodal
performance through extensive training. Deployed on smartphone NPUs, GenieBlue
demonstrates efficiency and practicality for applications on mobile devices.
