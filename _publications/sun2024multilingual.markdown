---
layout: publication
title: 'Fuxitranyu: A Multilingual Large Language Model Trained With Balanced Data'
authors: Sun Haoran, Jin Renren, Xu Shaoyang, Pan Leiyu, Supryadi, Cui Menglong, Du Jiangcun, Lei Yikun, Yang Lei, Shi Ling, Xiao Juesi, Zhu Shaolin, Xiong Deyi
conference: "Arxiv"
year: 2024
bibkey: sun2024multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.06273"}
tags: ['Fine Tuning', 'Interpretability And Explainability', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
"Large language models (LLMs) have demonstrated prowess in a wide range of tasks. However, many LLMs exhibit significant performance discrepancies between high- and low-resource languages. To mitigate this challenge, we present FuxiTranyu, an open-source multilingual LLM, which is designed to satisfy the need of the research community for balanced and high-performing multilingual capabilities. FuxiTranyu-8B, the base model with 8 billion parameters, is trained from scratch on a meticulously balanced multilingual data repository that contains 600 billion tokens covering 43 natural languages and 16 programming languages. In addition to the base model, we also develop two instruction-tuned models: FuxiTranyu-8B-SFT that is fine-tuned on a diverse multilingual instruction dataset, and FuxiTranyu-8B-DPO that is further refined with DPO on a preference dataset for enhanced alignment ability. Extensive experiments on a wide range of multilingual benchmarks demonstrate the competitive performance of FuxiTranyu against existing multilingual LLMs, e.g., BLOOM-7B, PolyLM-13B, Llama-2-Chat-7B and Mistral-7B-Instruct. Interpretability analyses at both the neuron and representation level suggest that FuxiTranyu is able to learn consistent multilingual representations across different languages. To promote further research into multilingual LLMs and their working mechanisms, we release both the base and instruction-tuned FuxiTranyu models together with 58 pretraining checkpoints at HuggingFace and Github."
