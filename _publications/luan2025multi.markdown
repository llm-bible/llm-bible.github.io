---
layout: publication
title: 'Multi-cue Adaptive Visual Token Pruning For Large Vision-language Models'
authors: Bozhi Luan, Wengang Zhou, Hao Feng, Zhe Wang, Xiaosong Li, Houqiang Li
conference: "Arxiv"
year: 2025
bibkey: luan2025multi
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.08019'}
  - {name: "Code", url: 'https://github.com/bzluan/AdaptPrune'}
tags: ['Attention Mechanism', 'Has Code', 'Efficiency and Optimization', 'Security', 'Model Architecture', 'Training Techniques', 'Pruning', 'Multimodal Models', 'Reinforcement Learning', 'Ethics and Bias']
---
As the computational needs of Large Vision-Language Models (LVLMs) increase,
visual token pruning has proven effective in improving inference speed and
memory efficiency. Traditional pruning methods in LVLMs predominantly focus on
attention scores to determine token relevance, overlooking critical aspects
such as spatial position and token similarity. To this end, we introduce
AdaptPrune, a novel plug-and-play training-free pruning method that builds on
conventional attention-based pruning by integrating spatial distance and token
similarity with an adaptive NMS approach. Our method is based on several
observed phenomena in large models: the positional bias in the model's image
attention and the redundancy of token information ignored by previous
approaches. By integrating attention, spatial, and similarity information, our
approach ensures a comprehensive evaluation of token importance and
substantially refines the pruning decisions. Our method has been extensively
tested across various LVLMs and benchmarks, confirming its robustness and
adaptability. The results demonstrate that AdaptPrune consistently outperforms
existing methods across various pruning ratios. Code is available at
https://github.com/bzluan/AdaptPrune.
