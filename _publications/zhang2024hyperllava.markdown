---
layout: publication
title: HyperLLaVA Dynamic Visual and Language Expert Tuning for Multimodal Large Language Models
authors: Zhang Wenqiao, Lin Tianwei, Liu Jiang, Shu Fangxun, Li Haoyuan, Zhang Lei, Wanggui He, Zhou Hao, Lv Zheqi, Jiang Hao, Li Juncheng, Tang Siliang, Zhuang Yueting
conference: "Arxiv"
year: 2024
bibkey: zhang2024hyperllava
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.13447"}
  - {name: "Code", url: "https://github.com/DCDmllm/HyperLLaVA"}
tags: ['Has Code', 'Multimodal Models', 'Reinforcement Learning', 'Training Techniques']
---
Recent advancements indicate that scaling up Multimodal Large Language Models (MLLMs) effectively enhances performance on downstream multimodal tasks. The prevailing MLLM paradigm emphe.g. LLaVA transforms visual features into text-like tokens using a emphstatic vision-language mapper thereby enabling emphstatic LLMs to develop the capability to comprehend visual information through visual instruction tuning. Although promising the emphstatic tuning strategy~footnoteThe static tuning refers to the trained model with static parameters. that shares the same parameters may constrain performance across different downstream multimodal tasks. In light of this we introduce HyperLLaVA which involves adaptive tuning of the projector and LLM parameters in conjunction with a dynamic visual expert and language expert respectively. These experts are derived from HyperNetworks which generates adaptive parameter shifts through visual and language guidance enabling dynamic projector and LLM modeling in two-stage training. Our experiments demonstrate that our solution significantly surpasses LLaVA on existing MLLM benchmarks including MME MMBench SEED-Bench and LLaVA-Bench. ~footnoteOur project is available on the link https://github.com/DCDmllm/HyperLLaVA.
