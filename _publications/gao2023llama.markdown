---
layout: publication
title: Llama45;adapter V2 Parameter45;efficient Visual Instruction Model
authors: Gao Peng, Han Jiaming, Zhang Renrui, Lin Ziyi, Geng Shijie, Zhou Aojun, Zhang Wei, Lu Pan, He Conghui, Yue Xiangyu, Li Hongsheng, Qiao Yu
conference: "Arxiv"
year: 2023
bibkey: gao2023llama
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.15010"}
  - {name: "Code", url: "https://github.com/ZrrSkywalker/LLaMA&#45;Adapter"}
tags: ['Ethics And Bias', 'GPT', 'Has Code', 'Merging', 'Model Architecture', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
How to efficiently transform large language models (LLMs) into instruction followers is recently a popular research direction while training LLM for multi45;modal reasoning remains less explored. Although the recent LLaMA45;Adapter demonstrates the potential to handle visual inputs with LLMs it still cannot generalize well to open45;ended visual instructions and lags behind GPT45;4. In this paper we present LLaMA45;Adapter V2 a parameter45;efficient visual instruction model. Specifically we first augment LLaMA45;Adapter by unlocking more learnable parameters (e.g. norm bias and scale) which distribute the instruction45;following ability across the entire LLaMA model besides adapters. Secondly we propose an early fusion strategy to feed visual tokens only into the early LLM layers contributing to better visual knowledge incorporation. Thirdly a joint training paradigm of image45;text pairs and instruction45;following data is introduced by optimizing disjoint groups of learnable parameters. This strategy effectively alleviates the interference between the two tasks of image45;text alignment and instruction following and achieves strong multi45;modal reasoning with only a small45;scale image45;text and instruction dataset. During inference we incorporate additional expert models (e.g. captioning/OCR systems) into LLaMA45;Adapter to further enhance its image understanding capability without incurring training costs. Compared to the original LLaMA45;Adapter our LLaMA45;Adapter V2 can perform open45;ended multi45;modal instructions by merely introducing 14M parameters over LLaMA. The newly designed framework also exhibits stronger language45;only instruction45;following capabilities and even excels in chat interactions. Our code and models are available at https://github.com/ZrrSkywalker/LLaMA&#45;Adapter.
