---
layout: publication
title: 'Preparing Lessons For Progressive Training On Language Models'
authors: Pan Yu, Yuan Ye, Yin Yichun, Shi Jiaxin, Xu Zenglin, Zhang Ming, Shang Lifeng, Jiang Xin, Liu Qun
conference: "Arxiv"
year: 2024
bibkey: pan2024preparing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.09192"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
The rapid progress of Transformers in artificial intelligence has come at the
cost of increased resource consumption and greenhouse gas emissions due to
growing model sizes. Prior work suggests using pretrained small models to
improve training efficiency, but this approach may not be suitable for new
model structures. On the other hand, training from scratch can be slow, and
progressively stacking layers often fails to achieve significant acceleration.
To address these challenges, we propose a novel method called Apollo, which
prep\textbf\{a\}res lessons for ex\textbf\{p\}anding \textbf\{o\}perations by
\textbf\{l\}earning high-\textbf\{l\}ayer functi\textbf\{o\}nality during training of
low layers. Our approach involves low-value-prioritized sampling (LVPS) to
train different depths and weight sharing to facilitate efficient expansion. We
also introduce an interpolation method for stable model depth extension.
Experiments demonstrate that Apollo achieves state-of-the-art acceleration
ratios, even rivaling methods using pretrained models, making it a universal
and efficient solution for training deep models while reducing time, financial,
and environmental costs.
