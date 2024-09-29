---
layout: publication
title: LISA Layerwise Importance Sampling For Memory45;efficient Large Language Model Fine45;tuning
authors: Pan Rui, Liu Xiang, Diao Shizhe, Pi Renjie, Zhang Jipeng, Han Chi, Zhang Tong
conference: "Arxiv"
year: 2024
bibkey: pan2024layerwise
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.17919"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Training Techniques']
---
The machine learning community has witnessed impressive advancements since large language models (LLMs) first appeared. Yet their massive memory consumption has become a significant roadblock to large45;scale training. For instance a 7B model typically requires at least 60 GB of GPU memory with full parameter training which presents challenges for researchers without access to high45;resource environments. Parameter Efficient Fine45;Tuning techniques such as Low45;Rank Adaptation (LoRA) have been proposed to alleviate this problem. However in most large45;scale fine45;tuning settings their performance does not reach the level of full parameter training because they confine the parameter search to a low45;rank subspace. Attempting to complement this deficiency we investigate the layerwise properties of LoRA on fine45;tuning tasks and observe an unexpected but consistent skewness of weight norms across different layers. Utilizing this key observation a surprisingly simple training strategy is discovered which outperforms both LoRA and full parameter training in a wide range of settings with memory costs as low as LoRA. We name it Layerwise Importance Sampled AdamW (LISA) a promising alternative for LoRA which applies the idea of importance sampling to different layers in LLMs and randomly freezes most middle layers during optimization. Experimental results show that with similar or less GPU memory consumption LISA surpasses LoRA or even full parameter tuning in downstream fine45;tuning tasks where LISA consistently outperforms LoRA by over 1037;45;3537; in terms of MT45;Bench score while achieving on45;par or better performance in MMLU AGIEval and WinoGrande. On large models specifically LLaMA45;245;70B LISA surpasses LoRA on MT45;Bench GSM8K and PubMedQA demonstrating its effectiveness across different domains.
