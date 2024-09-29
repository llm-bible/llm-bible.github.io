---
layout: publication
title: Octavius Mitigating Task Interference in MLLMs via LoRA-MoE
authors: Chen Zeren, Wang Ziqin, Wang Zhen, Liu Huayang, Yin Zhenfei, Liu Si, Sheng Lu, Ouyang Wanli, Qiao Yu, Shao Jing
conference: "Arxiv"
year: 2023
bibkey: chen2023octavius
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.02684"}
  - {name: "Code", url: "https://openlamm.github.io/paper_list/Octavius"}
tags: ['Fine Tuning', 'Has Code', 'Multimodal Models', 'Reinforcement Learning', 'Tools']
---
Recent studies have demonstrated Large Language Models (LLMs) can extend their zero-shot generalization capabilities to multimodal learning through instruction tuning. As more modalities and downstream tasks are introduced negative conflicts and interference may have a worse impact on performance. While this phenomenon has been overlooked in previous work we propose a novel and extensible framework called Octavius for comprehensive studies and experimentation on multimodal learning with Multimodal Large Language Models (MLLMs). Specifically we combine the well-known Mixture-of-Experts (MoE) and one of the representative PEFT techniques i.e. LoRA designing a novel LLM-based decoder called LoRA-MoE for multimodal learning. To the best of our knowledge we are one of the pioneering efforts to introduce MoE into MLLMs to address this problem. The experimental results (about 20 improvement) have shown the effectiveness and versatility of our design in various 2D and 3D downstream tasks. Code and datasets are available at https://openlamm.github.io/paper_list/Octavius.
