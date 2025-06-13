---
layout: publication
title: 'Adatp: Attention-debiased Token Pruning For Video Large Language Models'
authors: Fengyuan Sun, Leqi Shen, Hui Chen, Sicheng Zhao, Jungong Han, Guiguang Ding
conference: "Arxiv"
year: 2025
bibkey: sun2025attention
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.20100'}
tags: ['Attention Mechanism', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Pruning', 'Ethics and Bias']
---
Video Large Language Models (Video LLMs) have achieved remarkable results in video understanding tasks. However, they often suffer from heavy computational overhead due to the large number of visual tokens generated from multiple video frames. Existing visual token compression methods often rely on attention scores from language models as guidance. However, these scores exhibit inherent biases: global bias reflects a tendency to focus on the two ends of the visual token sequence, while local bias leads to an over-concentration on the same spatial positions across different frames. To address the issue of attention bias, we propose \\(\textbf\{A\}\\)ttention-\\(\textbf\{D\}\\)ebi\\(\textbf\{a\}\\)sed \\(\textbf\{T\}\\)oken \\(\textbf\{P\}\\)runing for Video Large Language Models (\\(\textbf\{AdaTP\}\\)), a novel token pruning pipeline for Video LLMs. AdaTP integrates two dedicated debiasing modules into the pipeline, targeting global attention bias and local attention bias, respectively. Without the need for additional training, our method significantly reduces the computational overhead of Video LLMs while retaining the performance of vanilla models. Extensive evaluation shows that AdaTP achieves state-of-the-art performance in various commonly used video understanding benchmarks. In particular, on LLaVA-OneVision-7B, AdaTP maintains performance without degradation while using only up to \\(27.3%\\) FLOPs compared to the vanilla model. Our code will be released soon.
