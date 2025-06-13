---
layout: publication
title: 'Cloq: Enhancing Fine-tuning Of Quantized Llms Via Calibrated Lora Initialization'
authors: Yanxia Deng, Aozhong Zhang, Naigang Wang, Selcuk Gurses, Zi Yang, Penghang Yin
conference: "Arxiv"
year: 2025
bibkey: deng2025enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.18475'}
tags: ['RAG', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Fine-tuning large language models (LLMs) using low-rank adaptation (LoRA) has
become a highly efficient approach for downstream tasks, particularly in
scenarios with limited computational resources. However, applying LoRA
techniques to quantized LLMs poses unique challenges due to the reduced
representational precision of quantized weights. In this paper, we introduce
CLoQ (Calibrated LoRA initialization for Quantized LLMs), a simplistic
initialization strategy designed to overcome these challenges. Our approach
focuses on minimizing the layer-wise discrepancy between the original LLM and
its quantized counterpart with LoRA components during initialization. By
leveraging a small calibration dataset, CLoQ quantizes a pre-trained LLM and
determines the optimal LoRA components for each layer, ensuring a strong
foundation for subsequent fine-tuning. A key contribution of this work is a
novel theoretical result that enables the accurate and closed-form construction
of these optimal LoRA components. We validate the efficacy of CLoQ across
multiple tasks such as language generation, arithmetic reasoning, and
commonsense reasoning, demonstrating that it consistently outperforms existing
LoRA fine-tuning methods for quantized LLMs, especially at ultra low-bit
widths.
