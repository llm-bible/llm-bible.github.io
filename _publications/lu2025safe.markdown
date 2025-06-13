---
layout: publication
title: 'Safe Delta: Consistently Preserving Safety When Fine-tuning Llms On Diverse Datasets'
authors: Ning Lu, Shengcai Liu, Jiahao Wu, Weiyu Chen, Zhirui Zhang, Yew-soon Ong, Qi Wang, Ke Tang
conference: "Arxiv"
year: 2025
bibkey: lu2025safe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12038"}
tags: ['Fine-Tuning', 'Responsible AI', 'Tools', 'Applications', 'RAG', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) have shown great potential as general-purpose AI assistants across various domains. To fully leverage this potential in specific applications, many companies provide fine-tuning API services, enabling users to upload their own data for LLM customization. However, fine-tuning services introduce a new safety threat: user-uploaded data, whether harmful or benign, can break the model's alignment, leading to unsafe outputs. Moreover, existing defense methods struggle to address the diversity of fine-tuning datasets (e.g., varying sizes, tasks), often sacrificing utility for safety or vice versa. To address this issue, we propose Safe Delta, a safety-aware post-training defense method that adjusts the delta parameters (i.e., the parameter change before and after fine-tuning). Specifically, Safe Delta estimates the safety degradation, selects delta parameters to maximize utility while limiting overall safety loss, and applies a safety compensation vector to mitigate residual safety loss. Through extensive experiments on four diverse datasets with varying settings, our approach consistently preserves safety while ensuring that the utility gain from benign datasets remains unaffected.
