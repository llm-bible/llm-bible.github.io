---
layout: publication
title: OlaGPT Empowering LLMs With Human-like Problem-Solving Abilities
authors: Xie Yuanzhen, Xie Tao, Lin Mingxiong, Wei Wentao, Li Chenglin, Kong Beibei, Chen Lei, Zhuo Chengxiang, Hu Bo, Li Zang
conference: "Arxiv"
year: 2023
bibkey: xie2023olagpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.16334"}
  - {name: "Code", url: "https://github.com/oladata-team/OlaGPT"}
tags: ['ARXIV', 'Attention Mechanism', 'GPT', 'Has Code', 'Interpretability', 'LLM', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools']
---
In most current research large language models (LLMs) are able to perform reasoning tasks by generating chains of thought through the guidance of specific prompts. However there still exists a significant discrepancy between their capability in solving complex reasoning problems and that of humans. At present most approaches focus on chains of thought (COT) and tool use without considering the adoption and application of human cognitive frameworks. It is well-known that when confronting complex reasoning challenges humans typically employ various cognitive abilities and necessitate interaction with all aspects of tools knowledge and the external environment information to accomplish intricate tasks. This paper introduces a novel intelligent framework referred to as OlaGPT. OlaGPT carefully studied a cognitive architecture framework and propose to simulate certain aspects of human cognition. The framework involves approximating different cognitive modules including attention memory reasoning learning and corresponding scheduling and decision-making mechanisms. Inspired by the active learning mechanism of human beings it proposes a learning unit to record previous mistakes and expert opinions and dynamically refer to them to strengthen their ability to solve similar problems. The paper also outlines common effective reasoning frameworks for human problem-solving and designs Chain-of-Thought (COT) templates accordingly. A comprehensive decision-making mechanism is also proposed to maximize model accuracy. The efficacy of OlaGPT has been stringently evaluated on multiple reasoning datasets and the experimental outcomes reveal that OlaGPT surpasses state-of-the-art benchmarks demonstrating its superior performance. Our implementation of OlaGPT is available on GitHub url https://github.com/oladata-team/OlaGPT.
