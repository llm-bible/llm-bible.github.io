---
layout: publication
title: 'Intention Analysis Makes Llms A Good Jailbreak Defender'
authors: Zhang Yuqi, Ding Liang, Zhang Lefei, Tao Dacheng
conference: "Arxiv"
year: 2024
bibkey: zhang2024intention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.06561"}
  - {name: "Code", url: "https://github.com/alphadl/SafeLLM_with_IntentionAnalysis"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Responsible AI', 'Security']
---
'Aligning large language models (LLMs) with human values, particularly in the face of complex and stealthy jailbreak attacks, presents a formidable challenge. In this study, we present a simple yet highly effective defense strategy, i.e., Intention Analysis (\(\mathbb{IA}\)). The principle behind this is to trigger LLMs'' inherent self-correct and improve ability through a two-stage process: 1) essential intention analysis, and 2) policy-aligned response. Notably, \(\mathbb{IA}\) is an inference-only method, thus could enhance the safety of LLMs without compromising their helpfulness. Extensive experiments on varying jailbreak benchmarks across ChatGLM, LLaMA2, Vicuna, MPT, DeepSeek, and GPT-3.5 show that \(\mathbb{IA}\) could consistently and significantly reduce the harmfulness in responses (averagely -53.1&#37; attack success rate) and maintain the general helpfulness. Encouragingly, with the help of our \(\mathbb{IA}\), Vicuna-7B even outperforms GPT-3.5 in terms of attack success rate. Further analyses present some insights into how our method works. To facilitate reproducibility, we release our code and scripts at: https://github.com/alphadl/SafeLLM\_with\_IntentionAnalysis.'
