---
layout: publication
title: 'Ssr-zero: Simple Self-rewarding Reinforcement Learning For Machine Translation'
authors: Wenjie Yang, Mao Zheng, Mingyang Song, Zheng Li
conference: "Arxiv"
year: 2025
bibkey: yang2025ssr
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16637"}
tags: ['Agentic', 'WMT', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Applications']
---
Large language models (LLMs) have recently demonstrated remarkable capabilities in machine translation (MT). However, most advanced MT-specific LLMs heavily rely on external supervision signals during training, such as human-annotated reference data or trained reward models (RMs), which are often expensive to obtain and challenging to scale. To overcome this limitation, we propose a Simple Self-Rewarding (SSR) Reinforcement Learning (RL) framework for MT that is reference-free, fully online, and relies solely on self-judging rewards. Training with SSR using 13K monolingual examples and Qwen-2.5-7B as the backbone, our model SSR-Zero-7B outperforms existing MT-specific LLMs, e.g., TowerInstruct-13B and GemmaX-28-9B, as well as larger general LLMs like Qwen2.5-32B-Instruct in English \\(\leftrightarrow\\) Chinese translation tasks from WMT23, WMT24, and Flores200 benchmarks. Furthermore, by augmenting SSR with external supervision from COMET, our strongest model, SSR-X-Zero-7B, achieves state-of-the-art performance in English \\(\leftrightarrow\\) Chinese translation, surpassing all existing open-source models under 72B parameters and even outperforming closed-source models, e.g., GPT-4o and Gemini 1.5 Pro. Our analysis highlights the effectiveness of the self-rewarding mechanism compared to the external LLM-as-a-judge approach in MT and demonstrates its complementary benefits when combined with trained RMs. Our findings provide valuable insight into the potential of self-improving RL methods. We have publicly released our code, data and models.
