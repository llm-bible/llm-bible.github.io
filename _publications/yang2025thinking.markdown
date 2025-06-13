---
layout: publication
title: 'Thinking Preference Optimization'
authors: Wang Yang, Hongye Jin, Jingfeng Yang, Vipin Chaudhary, Xiaotian Han
conference: "Arxiv"
year: 2025
bibkey: yang2025thinking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.13173'}
tags: ['RAG', 'Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Supervised Fine-Tuning (SFT) has been a go-to and effective method for
enhancing long chain-of-thought (CoT) reasoning in relatively small LLMs by
fine-tuning them with long CoT responses from larger LLMs. To continually
improve reasoning abilities, we can either collect new high-quality long CoT
reasoning SFT data or repeatedly train on existing SFT datasets. However,
acquiring new long CoT SFT data is costly and limited, while repeated training
often results in a performance plateau or decline. To further boost the
performance with the SFT data, we propose Thinking Preference Optimization
(ThinkPO), a simple yet effective post-SFT method that enhances long CoT
reasoning without requiring new long CoT responses. Instead, ThinkPO utilizes
readily available or easily obtainable short CoT reasoning responses as
rejected answers and long CoT responses as chosen answers for the same
question. It then applies direct preference optimization to encourage the model
to favor longer reasoning outputs. Experiments show that ThinkPO further
improves the reasoning performance of SFT-ed models, e.g. it increases math
reasoning accuracy of SFT-ed models by 8.6% and output length by 25.9%.
Notably, ThinkPO is capable of continually boosting the performance of the
publicly distilled SFT model, e.g., increasing the official
DeepSeek-R1-Distill-Qwen-7B's performance on MATH500 from 87.4% to 91.2%.
