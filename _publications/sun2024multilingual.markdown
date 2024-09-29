---
layout: publication
title: Fuxitranyu A Multilingual Large Language Model Trained With Balanced Data
authors: Sun Haoran, Jin Renren, Xu Shaoyang, Pan Leiyu, Supryadi, Cui Menglong, Du Jiangcun, Lei Yikun, Yang Lei, Shi Ling, Xiao Juesi, Zhu Shaolin, Xiong Deyi
conference: "Arxiv"
year: 2024
bibkey: sun2024multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.06273"}
tags: ['Fine Tuning', 'Interpretability And Explainability', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) have demonstrated prowess in a wide range of tasks. However many LLMs exhibit significant performance discrepancies between high45; and low45;resource languages. To mitigate this challenge we present FuxiTranyu an open45;source multilingual LLM which is designed to satisfy the need of the research community for balanced and high45;performing multilingual capabilities. FuxiTranyu45;8B the base model with 8 billion parameters is trained from scratch on a meticulously balanced multilingual data repository that contains 600 billion tokens covering 43 natural languages and 16 programming languages. In addition to the base model we also develop two instruction45;tuned models FuxiTranyu45;8B45;SFT that is fine45;tuned on a diverse multilingual instruction dataset and FuxiTranyu45;8B45;DPO that is further refined with DPO on a preference dataset for enhanced alignment ability. Extensive experiments on a wide range of multilingual benchmarks demonstrate the competitive performance of FuxiTranyu against existing multilingual LLMs e.g. BLOOM45;7B PolyLM45;13B Llama45;245;Chat45;7B and Mistral45;7B45;Instruct. Interpretability analyses at both the neuron and representation level suggest that FuxiTranyu is able to learn consistent multilingual representations across different languages. To promote further research into multilingual LLMs and their working mechanisms we release both the base and instruction45;tuned FuxiTranyu models together with 58 pretraining checkpoints at HuggingFace and Github.
