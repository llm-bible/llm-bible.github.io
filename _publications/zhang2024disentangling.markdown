---
layout: publication
title: 'Disentangling Preference Representation And Text Generation For Efficient Individual Preference Alignment'
authors: Jianfei Zhang, Jun Bai, Bei Li, Yanmeng Wang, Rumei Li, Chenghua Lin, Wenge Rong
conference: "Arxiv"
year: 2024
bibkey: zhang2024disentangling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.20834"}
tags: ['Language Modeling', 'Training Techniques', 'Applications', 'Efficiency and Optimization']
---
Aligning Large Language Models (LLMs) with general human preferences has been
proved crucial in improving the interaction quality between LLMs and human.
However, human values are inherently diverse among different individuals,
making it insufficient to align LLMs solely with general preferences. To
address this, personalizing LLMs according to individual feedback emerges as a
promising solution. Nonetheless, this approach presents challenges in terms of
the efficiency of alignment algorithms. In this work, we introduce a flexible
paradigm for individual preference alignment. Our method fundamentally improves
efficiency by disentangling preference representation from text generation in
LLMs. We validate our approach across multiple text generation tasks and
demonstrate that it can produce aligned quality as well as or better than
PEFT-based methods, while reducing additional training time for each new
individual preference by \\(80%\\) to \\(90%\\) in comparison with them.
