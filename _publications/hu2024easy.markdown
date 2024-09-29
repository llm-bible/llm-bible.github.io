---
layout: publication
title: Openrlhf An Easy-to-use Scalable And High-performance RLHF Framework
authors: Hu Jian, Wu Xibin, Wang Weixun, Xianyu, Zhang Dehao, Cao Yu
conference: "Arxiv"
year: 2024
bibkey: hu2024easy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.11143"}
  - {name: "Code", url: "https://github.com/OpenRLHF/OpenRLHF\"}
tags: ['Agentic', 'Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Large Scale Training', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Scaling Laws', 'Tools', 'Training Techniques']
---
As large language models (LLMs) continue to grow by scaling laws reinforcement learning from human feedback (RLHF) has gained significant attention due to its outstanding performance. However unlike pretraining or fine-tuning a single model scaling reinforcement learning from human feedback (RLHF) for training large language models poses coordination challenges across four models. We present OpenRLHF an open-source framework enabling efficient RLHF scaling. Unlike existing RLHF frameworks that co-locate four models on the same GPUs OpenRLHF re-designs scheduling for the models beyond 70B parameters using Ray vLLM and DeepSpeed leveraging improved resource utilization and diverse training approaches. Integrating seamlessly with Hugging Face OpenRLHF provides an out-of-the-box solution with optimized algorithms and launch scripts which ensures user-friendliness. OpenRLHF implements RLHF DPO rejection sampling and other alignment techniques. Empowering state-of-the-art LLM development OpenRLHFs code is available at (url)https://github.com/OpenRLHF/OpenRLHF\}.
