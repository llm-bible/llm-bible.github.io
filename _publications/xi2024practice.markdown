---
layout: publication
title: 'A Practice Of Post-training On Llama-3 70B With Optimal Selection Of Additional Language Mixture Ratio'
authors: Xi Ningyuan, Wu Yetao, Fan Kun, Chen Teng, Gu Qingqing, Yu Peng, Qu Jinxian, Liu Chenxi, Jiang Zhonglin, Chen Yong, Ji Luo
conference: "Arxiv"
year: 2024
bibkey: xi2024practice
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.06624"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
Large Language Models (LLM) often needs to be Continual Pre-Trained (CPT) to obtain the unfamiliar language skill or adapt into new domains. The huge training cost of CPT often asks for cautious choice of key hyper-parameters such as the mixture ratio of extra language or domain corpus. However, there is no systematic study which bridge the gap between the optimal mixture ratio and the actual model performance, and the gap between experimental scaling law and the actual deployment in the full model size. In this paper, we perform CPT on Llama-3 8B and 70B to enhance its Chinese ability. We study the optimal correlation between the Additional Language Mixture Ratio (ALMR) and the Learning Rate (LR) on the 8B size which directly indicate the optimal experimental set up. By thorough choice of hyper-parameter, and subsequent fine-tuning, the model capability is improved not only on the Chinese-related benchmark, but also some specific domains including math, coding and emotional intelligence. We deploy the final 70B version of LLM on an real-life chat system which obtain satisfying performance.
