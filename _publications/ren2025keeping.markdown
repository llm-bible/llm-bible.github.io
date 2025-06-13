---
layout: publication
title: 'Keeping An Eye On LLM Unlearning: The Hidden Risk And Remedy'
authors: Jie Ren, Zhenwei Dai, Xianfeng Tang, Yue Xing, Shenglai Zeng, Hui Liu, Jingying Zeng, Qiankun Peng, Samarth Varshney, Suhang Wang, Qi He, Charu C. Aggarwal, Hui Liu
conference: "Arxiv"
year: 2025
bibkey: ren2025keeping
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.00359'}
tags: ['RAG', 'Security', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Although Large Language Models (LLMs) have demonstrated impressive capabilities across a wide range of tasks, growing concerns have emerged over the misuse of sensitive, copyrighted, or harmful data during training. To address these concerns, unlearning techniques have been developed to remove the influence of specific data without retraining from scratch. However, this paper reveals a critical vulnerability in fine-tuning-based unlearning: a malicious user can craft a manipulated forgetting request that stealthily degrades the model's utility for benign users. We demonstrate this risk through a red-teaming Stealthy Attack (SA), which is inspired by two key limitations of existing unlearning (the inability to constrain the scope of unlearning effect and the failure to distinguish benign tokens from unlearning signals). Prior work has shown that unlearned models tend to memorize forgetting data as unlearning signals, and respond with hallucinations or feigned ignorance when unlearning signals appear in the input. By subtly increasing the presence of common benign tokens in the forgetting data, SA enhances the connection between benign tokens and unlearning signals. As a result, when normal users include such tokens in their prompts, the model exhibits unlearning behaviors, leading to unintended utility degradation. To address this vulnerability, we propose Scope-aware Unlearning (SU), a lightweight enhancement that introduces a scope term into the unlearning objective, encouraging the model to localize the forgetting effect. Our method requires no additional data processing, integrates seamlessly with existing fine-tuning frameworks, and significantly improves robustness against SA. Extensive experiments validate the effectiveness of both SA and SU.
