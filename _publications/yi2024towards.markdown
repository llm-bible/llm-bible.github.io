---
layout: publication
title: 'Towards Fast Multilingual LLM Inference: Speculative Decoding And Specialized Drafters'
authors: Yi Euiin, Kim Taehyeon, Jeung Hongseok, Chang Du-seong, Yun Se-young
conference: "Arxiv"
year: 2024
bibkey: yi2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16758"}
tags: ['Applications', 'GPT', 'Model Architecture', 'RAG', 'Training Techniques', 'Uncategorized']
---
Large language models (LLMs) have revolutionized natural language processing and broadened their applicability across diverse commercial applications. However, the deployment of these models is constrained by high inference time in multilingual settings. To mitigate this challenge, this paper explores a training recipe of an assistant model in speculative decoding, which are leveraged to draft and-then its future tokens are verified by the target LLM. We show that language-specific draft models, optimized through a targeted pretrain-and-finetune strategy, substantially brings a speedup of inference time compared to the previous methods. We validate these models across various languages in inference time, out-of-domain speedup, and GPT-4o evaluation.
