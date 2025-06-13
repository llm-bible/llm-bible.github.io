---
layout: publication
title: 'Hermesflow: Seamlessly Closing The Gap In Multimodal Understanding And Generation'
authors: Ling Yang, Xinchen Zhang, Ye Tian, Chenming Shang, Minghao Xu, Wentao Zhang, Bin Cui
conference: "Arxiv"
year: 2025
bibkey: yang2025seamlessly
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12148"}
  - {name: "Code", url: "https://github.com/Gen-Verse/HermesFlow"}
tags: ['Efficiency and Optimization', 'Multimodal Models', 'Tools', 'Reinforcement Learning', 'Merging', 'GPT', 'Pretraining Methods', 'Has Code']
---
The remarkable success of the autoregressive paradigm has made significant
advancement in Multimodal Large Language Models (MLLMs), with powerful models
like Show-o, Transfusion and Emu3 achieving notable progress in unified image
understanding and generation. For the first time, we uncover a common
phenomenon: the understanding capabilities of MLLMs are typically stronger than
their generative capabilities, with a significant gap between the two. Building
on this insight, we propose HermesFlow, a simple yet general framework designed
to seamlessly bridge the gap between understanding and generation in MLLMs.
Specifically, we take the homologous data as input to curate homologous
preference data of both understanding and generation. Through Pair-DPO and
self-play iterative optimization, HermesFlow effectively aligns multimodal
understanding and generation using homologous preference data. Extensive
experiments demonstrate the significant superiority of our approach over prior
methods, particularly in narrowing the gap between multimodal understanding and
generation. These findings highlight the potential of HermesFlow as a general
alignment framework for next-generation multimodal foundation models. Code:
https://github.com/Gen-Verse/HermesFlow
