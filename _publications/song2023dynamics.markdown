---
layout: publication
title: 'Dynamics Of Instruction Fine-tuning For Chinese Large Language Models'
authors: Chiyu Song, Zhanchao Zhou, Jianhao Yan, Yuejiao Fei, Zhenzhong Lan, Yue Zhang
conference: "Arxiv"
year: 2023
bibkey: song2023dynamics
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.19651"}
tags: ['Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Instruction tuning is a burgeoning method to elicit the general intelligence
of Large Language Models (LLMs). While numerous studies have examined the
impact of factors such as data volume and model size on English models, the
scaling properties of instruction tuning in other languages remain largely
unexplored. In this work, we systematically investigate the effects of data
quantity, model size, and data construction methods on instruction tuning for
Chinese LLMs. We utilize a newly curated dataset, DoIT, which includes over
40,000 high-quality instruction instances covering ten underlying abilities,
such as creative writing, code generation, and logical reasoning. Our
experiments, conducted on models ranging from 7b to 33b parameters, yield three
key findings: (i) While these factors directly affect overall model
performance, some abilities are more responsive to scaling, whereas others
demonstrate significant resistance. (ii) The scaling sensitivity of different
abilities to these factors can be explained by two features: Complexity and
Transference. (iii) By tailoring training strategies to their varying
sensitivities, specific abilities can be efficiently learned, enhancing
performance on two public benchmarks.
