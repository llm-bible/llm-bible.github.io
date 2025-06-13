---
layout: publication
title: 'Baichuan-audio: A Unified Framework For End-to-end Speech Interaction'
authors: Tianpeng Li, Jun Liu, Tao Zhang, Yuanbo Fang, Da Pan, Mingrui Wang, Zheng Liang, Zehuan Li, Mingan Lin, Guosheng Dong, Jianhua Xu, Haoze Sun, Zenan Zhou, Weipeng Chen
conference: "Arxiv"
year: 2025
bibkey: li2025baichuan
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.17239'}
  - {name: "Code", url: 'https://github.com/baichuan-inc/Baichuan-Audio'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Pre-Training']
---
We introduce Baichuan-Audio, an end-to-end audio large language model that
seamlessly integrates audio understanding and generation. It features a
text-guided aligned speech generation mechanism, enabling real-time speech
interaction with both comprehension and generation capabilities. Baichuan-Audio
leverages a pre-trained ASR model, followed by multi-codebook discretization of
speech at a frame rate of 12.5 Hz. This multi-codebook setup ensures that
speech tokens retain both semantic and acoustic information. To further enhance
modeling, an independent audio head is employed to process audio tokens,
effectively capturing their unique characteristics. To mitigate the loss of
intelligence during pre-training and preserve the original capabilities of the
LLM, we propose a two-stage pre-training strategy that maintains language
understanding while enhancing audio modeling. Following alignment, the model
excels in real-time speech-based conversation and exhibits outstanding
question-answering capabilities, demonstrating its versatility and efficiency.
The proposed model demonstrates superior performance in real-time spoken
dialogue and exhibits strong question-answering abilities. Our code, model and
training data are available at https://github.com/baichuan-inc/Baichuan-Audio
