---
layout: publication
title: GEB-1.3B\: Open Lightweight Large Language Model
authors: Wu Jie, Zhu Yufeng, Shen Lei, Lu Xuqing
conference: "Arxiv"
year: 2024
bibkey: wu2024geb
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.09900"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Quantization', 'Training Techniques']
---
Recently developed large language models (LLMs) such as ChatGPT Claude and Llama have demonstrated impressive abilities and even surpass human-level performance in several tasks. Despite their success the resource-intensive demands of these models requiring significant computational power for both training and inference limit their deployment to high-performance servers. Additionally the extensive calculation requirements of the models often lead to increased latency in response times. With the increasing need for LLMs to operate efficiently on CPUs research about lightweight models that are optimized for CPU inference has emerged. In this work we introduce GEB-1.3B a lightweight LLM trained on 550 billion tokens in both Chinese and English languages. We employ novel training techniques including ROPE Group-Query-Attention and FlashAttention-2 to accelerate training while maintaining model performance. Additionally we fine-tune the model using 10 million samples of instruction data to enhance alignment. GEB-1.3B exhibits outstanding performance on general benchmarks such as MMLU C-Eval and CMMLU outperforming comparative models such as MindLLM-1.3B and TinyLLaMA-1.1B. Notably the FP32 version of GEB-1.3B achieves commendable inference times on CPUs with ongoing efforts to further enhance speed through advanced quantization techniques. The release of GEB-1.3B as an open-source model marks a significant contribution to the development of lightweight LLMs promising to foster further research and innovation in the field.
