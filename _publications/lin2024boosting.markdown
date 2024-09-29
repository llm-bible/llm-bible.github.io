---
layout: publication
title: Boosting Multimodal Large Language Models With Visual Tokens Withdrawal For Rapid Inference
authors: Lin Zhihang, Lin Mingbao, Lin Luxi, Ji Rongrong
conference: "Arxiv"
year: 2024
bibkey: lin2024boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.05803"}
  - {name: "Code", url: "https://github.com/lzhxmu/VTW"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Tools']
---
Multimodal large language models (MLLMs) demand considerable computations for inference due to the extensive parameters and the additional input tokens needed for visual information representation. Herein we introduce Visual Tokens Withdrawal (VTW) a plug-and-play module to boost MLLMs for rapid inference. Our approach is inspired by two intriguing phenomena we have observed (1) the attention sink phenomenon that is prevalent in LLMs also persists in MLLMs suggesting that initial tokens and nearest tokens receive the majority of attention while middle vision tokens garner minimal attention in deep layers; (2) the presence of information migration which implies that visual information is transferred to subsequent text tokens within the first few layers of MLLMs. As per our findings we conclude that vision tokens are unnecessary in the deep layers of MLLMs. Thus we strategically withdraw them at a certain layer enabling only text tokens to engage in subsequent layers. To pinpoint the ideal layer for VTW we initially analyze a limited set of tiny datasets and choose the first layer that meets the Kullback-Leibler divergence criterion. Our VTW approach can cut computational overhead by over 4037; across diverse multimodal tasks while maintaining performance. Our code is released at (url)https://github.com/lzhxmu/VTW\}."
