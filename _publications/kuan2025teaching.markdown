---
layout: publication
title: 'Teaching Audio-aware Large Language Models What Does Not Hear: Mitigating Hallucinations Through Synthesized Negative Samples'
authors: Chun-yi Kuan, Hung-yi Lee
conference: "Arxiv"
year: 2025
bibkey: kuan2025teaching
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.14518'}
tags: ['Reinforcement Learning', 'Training Techniques', 'Applications']
---
Recent advancements in audio-aware large language models (ALLMs) enable them to process and understand audio inputs. However, these models often hallucinate non-existent sound events, reducing their reliability in real-world applications. To address this, we propose LISTEN (Learning to Identify Sounds Through Extended Negative Samples), a contrastive-like training method that enhances ALLMs' ability to distinguish between present and absent sounds using synthesized data from the backbone LLM. Unlike prior approaches, our method requires no modification to LLM parameters and efficiently integrates audio representations via a lightweight adapter. Experiments show that LISTEN effectively mitigates hallucinations while maintaining impressive performance on existing audio question and reasoning benchmarks. At the same time, it is more efficient in both data and computation.
