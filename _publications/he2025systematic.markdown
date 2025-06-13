---
layout: publication
title: 'AIR: A Systematic Analysis Of Annotations, Instructions, And Response Pairs In Preference Dataset'
authors: Bingxiang He, Wenbin Zhang, Jiaxi Song, Cheng Qian, Zixuan Fu, Bowen Sun, Ning Ding, Haiwen Hong, Longtao Huang, Hui Xue, Ganqu Cui, Wanxiang Che, Zhiyuan Liu, Maosong Sun
conference: "Arxiv"
year: 2025
bibkey: he2025systematic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.03612'}
tags: ['RAG', 'Efficiency and Optimization', 'Tools']
---
Preference learning is critical for aligning large language models (LLMs)
with human values, yet its success hinges on high-quality datasets comprising
three core components: Preference \textbf\{A\}nnotations, \textbf\{I\}nstructions,
and \textbf\{R\}esponse Pairs. Current approaches conflate these components,
obscuring their individual impacts and hindering systematic optimization. In
this work, we propose \textbf\{AIR\}, a component-wise analysis framework that
systematically isolates and optimizes each component while evaluating their
synergistic effects. Through rigorous experimentation, AIR reveals actionable
principles: annotation simplicity (point-wise generative scoring), instruction
inference stability (variance-based filtering across LLMs), and response pair
quality (moderate margins + high absolute scores). When combined, these
principles yield +5.3 average gains over baseline method, even with only 14k
high-quality pairs. Our work shifts preference dataset design from ad hoc
scaling to component-aware optimization, offering a blueprint for efficient,
reproducible alignment.
